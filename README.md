# How to run

1. `docker run --rm -p 6831:6831/udp -p 6832:6832/udp -p 16686:16686 jaegertracing/all-in-one:1.40.0`
2. `python3 core.py`
3. `python3 orchestrator.py`
4. `curl http://localhost:8080/create-node?token=123`
5. Visit <http://localhost:16686> and see the trace magic.
