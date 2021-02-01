# elixir

Introduction to Elixir language. Running scripts.

Elixir is a dynamic, functional language designed for building scalable and maintainable applications.

Elixir leverages the Erlang VM, known for running low-latency, distributed and fault-tolerant systems, while also being successfully used in web development, embedded software, data ingestion, and multimedia processing domains across a wide range of industries.

Suppose you have an iot device, something like a weather sensor, that is deployed around the world to collect the weather data, maybe around 1 million devices. These devices send the collected data to the server at specific time intervals. For a typical scenario, some may consider doing a rewrite of the existing code base to make it more distributed and scalable for the future.

Well, elixir could do a lot more here, using erlang’s OTP you could actually manage around 1.5 million devices with a 40 Core-Server and the language comes with an addon to make it distributed, Seems amazing right !!!.

Ubuntu 14.04/16.04/17.04/18.04/19.04 or Debian 7/8/9/10

Add Erlang Solutions repository: 

wget https://packages.erlang-solutions.com/erlang-solutions_2.0_all.deb && sudo dpkg -i erlang-solutions_2.0_all.deb

Run: sudo apt-get update

Install the Erlang/OTP platform and all of its applications: sudo apt-get install esl-erlang

Install Elixir: sudo apt-get install elixir

Ref Link :: https://elixir-lang.org/install.html
