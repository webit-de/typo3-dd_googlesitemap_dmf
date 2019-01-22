Google sitemaps for TYPO3
======================

---

:raised_hand: :information_source: This is a fork of the TYPO3 extension
»[dd_googlesitemap_dmf](https://github.com/dohomi/dd_googlesitemap_dmf)« to send pull requests.

To use a patch version of this repository instead of the official release use these commands:

    composer config repositories.dd-googlesitemap-dmf-patch-version vcs https://github.com/webit-de/typo3-dd_googlesitemap_dmf.git
    composer require dmf/dd-googlesitemap-dmf "dev-2.0.0_patched as 2.0.0"

---


This is a "dd_googlesitemap_dmf" TYPO3 extension. You will need a TYPO3 CMS and "dd_googlesitemap" to run it. It extends the functionality of dd_googlesitemap for own extensions.

What does it do?
----------------
This extension adds sitemaps for typo3 extensions and is preconfigured with tx_news. Typically you add the result to Google like http://example.com/index.php?eID=dd_googlesitemap.

Manual
----------
Please read the manual inside of doc/manual.sxw where you find all information about installation and configuration.

Important
---------
Version 1.2.3 is only working with TYPO3 >= 6.2 and dd_googlesitemap >= 2.x

Contact
-------
E-mail: djgarms@gmail.com
