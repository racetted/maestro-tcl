
PACKAGES=Tktable2.10 bwidget-1.9.5 keynav1.0 tDOM-0.8.3 tablelist5.5 tcl8.5.11 tcllib-1.13 thread2.6.7 tk8.5.11  tkimg1.4 tklib-0.5


all:
	./INSTALL.sh

clean: 
	rm -rf $(PACKAGES)
	rm -rf ../bin/* ../lib/* ../include/*

distclean: clean
	rm -fr bin/$(BASE_ARCH) ; \
	find . -name "*~" -exec rm -f {} \;
