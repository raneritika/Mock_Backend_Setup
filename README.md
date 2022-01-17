# Mock Backend Setup- EC2 instance

The project statement was to setup a backend mock to an EC2 instance. For doing this the following steps need to be followed:

1. Create instance and launch.
2. Configure Security group inbound rules to apply to all(HTTP, TCP, SSH)
3. Connect to instance using EC2 Instance connect
4. Check for node and npm. Then run the main file(app.js)
5. After successful execution, copy the Public IPv4 address from the instances page and append port:3000 at the end on the web browser followed by data/2.5/weather.
6. Now we would be able to see the weather results.
