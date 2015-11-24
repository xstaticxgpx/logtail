# logtail
SYSV init script for maintaining tail pipes

Utilizes bash associative array for easy scalability.

Designed to be used in tandem with [zmqpush](https://github.comcast.com/gpacui001c/zmqpush) to ship logs via ZeroMQ to a Logstash cluster
