# Jewellery Image Training

Flask API for jewellery image matching using the Model 3 ONNX runtime and Supabase-backed catalogue data.

## Run the API

Install dependencies with `pip install -r requirements.txt`, configure the required Supabase and catalogue environment variables, then start the service with `python -m backend.app`.

The ONNX model is stored at `models/jewellery_model3.onnx`. Set `MODEL_PATH` if you store it elsewhere.
