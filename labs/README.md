### Labs

#### ENV setup

0. Remote server: `ssh a100` OR `ssh -L 8889:localhost:8888 user@a100.ip`

1. Option 1:
   - Conda: `conda create -n LLM_RAG python=3.10`
   - Activate env: `conda activate LLM_RAG`
2. Option 2:
   - venv: `python -m venv venv`
   - `source venv/bin/activate`

3. Install requirements: `pip install -r requirements.txt`
4. Run notebook: `jupyter lab --no-browser --port=8888 --ip=0.0.0.0`
