- Chybějící `Inline` a `Inline::Python` způsobí, že OpenQA nemůže využít testy psané v Pythonu a celý Test Job skončí chybou.
- Řešení - Doinstalování packagů
	- `sudo zypper install perl-Inline`
	- `sudo zypper install perl-Inline-Python`
- Pro maximální obejití Perlu musíme v `main.pm` distribuce nahrávat `main.py` -> [[BP/Problemy/Main.pm]]