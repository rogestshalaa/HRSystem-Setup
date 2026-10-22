# HRSystem Setup

Ky repo mban vetëm **setup-in e Windows** të HRSystem. Skedari i setup-it (`HRSystem<version>-Setup.zip`) është te **Releases**, jo në git.

## Si instalohet në një kompjuter të ri (pa USB)

1. Hap **Releases** të këtij repo dhe shkarko zip-in e fundit (`HRSystemV…-Setup.zip`).
2. Nxirre zip-in në një folder (p.sh. Desktop).
3. Kliko dy herë **Install.bat** (Run as administrator).
4. Dritarja kërkon vetëm folderin, pronarin e parë (përdorues, emër, fjalëkalim) dhe biznesin (emër, logo, ikonë). Databaza, Node.js dhe MySQL bëhen vetë.

Heqja: **Uninstall.bat** (zgjedh a ruhet databaza; ndalon vetë aplikacionin).

## Çfarë ka brenda zip-it

`Install.bat`, `Uninstall.bat`, `Dashboard.bat` dhe folderi `files` (skriptet e instalimit, dashboard-i dhe aplikacioni).

## Rregull

Ky repo nuk mban kod aplikacioni, dashboard-i apo tokena. Programi jeton te repot e klientëve (p.sh. `HRSystem-ReginaCenter`), dashboard-i te `HRSystem-Dashboard`. Zip-i ndërtohet nga pronari me `pack.py --setup-only <version> --publish`.

---

English: this repository holds only the HRSystem Windows setup zip (see Releases). Download it, extract, run `Install.bat` as administrator.
