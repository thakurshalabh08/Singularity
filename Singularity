BootStrap: docker
From: ubuntu:16.04

%help
	This is a test container.

%environment
	LC_ALL=C
	PERL5LIB=/usr/share/perl5:/usr/share/perl/5.22.1:/usr/local/share/perl/5.22.1
	MUGSY_INSTALL=/usr/local/bin

%post
	apt-get update
	apt -y install gcc
	apt -y install g++
	apt -y install make
	cpan install IO::File
