##Android Platform Knife

This is an almost dead project, just for personal debug use.

I think you should use Ubuntu desktop since Android native arch changed so fast and a lot

-----------------------------------------------------------------------------------------------------------------------------------------------------------

#### How to build?

	cd android-platform-knife/
	make -f Makefile.$(your-platform) CROSS_COMPILE=$(if-you-need)
	find what you build in ./output/bin/

#### How to use?
	cp all ./output/bin/* to your PATH

	or you can use my prebuild

	on Linux:
	source ./setenv.sh

	on Windows:
	.\setenv.bat
