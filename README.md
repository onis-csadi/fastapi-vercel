# FastAPI on Vercel Example

This is [FastAPI](https://fastapi.tiangolo.com/) example app deployed on [Vercel](https://vercel.com/).

### Requirements

- Vercel account
- [Vercel CLI](https://vercel.com/cli)

### Create environment

```bash
python -m venv env
```

### Activate environment (Unix)

```bash
source env/bin/activate
```

### Activate environment (Windows)

```bash
./env/Scripts/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run locally

```bash
uvicorn main:app --reload
```

### Deploy to Vercel

```bash
vercel
```
