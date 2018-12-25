### Basic 001 grpc python 

Don't know for some reason, i found grpc not directly coming to my head like rest used to feel. People say it's good, they say protocol buffers are better optimised, they feel so. So for me whole process is not so intitutive.

Slowly decoupling things.


To run it: 

Step 1: Install grpc tools: `pip install -r requirements.txt`

Step 2: Compile the proto file: `make compile-proto`

Step 3: Run grpc server: `python greeter-server.py`

Step 3: Run grpc client: `python greeter-client.py`
