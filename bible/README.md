# Bible text for The AFM HUB app

Built from eBible.org with `ministry-app/scripts/build-bible.py`. The app downloads each file once and keeps it on the phone for offline reading.

Public domain:
- `kjv.json` King James Version (`eng-kjv2006`)
- `bsb.json` Berean Standard Bible (`engbsb`, dedicated to the public domain)
- `msb.json` Majority Standard Bible (`engmsb`, dedicated to the public domain)
- `web.json` World English Bible (`engwebp`) and `webbe.json` World English Bible British Edition (`engwebpb`); "World English Bible" is a trademark of eBible.org
- `asv.json` American Standard Version (`eng-asv`)
- `webster.json` Webster Bible (`engwebster`)
- `bbe.json` Bible in Basic English (`engBBE`)
- `ylt.json` Young's Literal Translation (`engylt`)
- `dby.json` Darby Translation (`engDBY`)
- `gnv.json` Geneva Bible 1599 (`enggnv`)
- `lsg.json` Louis Segond 1910 (`fraLSG`)

CC BY-SA 4.0 (credit shown in the app):
- `lsv.json` Literal Standard Version (`englsv`) © Covenant Press
- `twi.json` Akuapem Twi (`twi`), `asante.json` Asante Twi (`twiasante`), `ewe.json` Ewe (`ewe`), `hau.json` Hausa (`hausa`) © Biblica, Inc.

Format: `{"books":[{"id":"GEN","name":"Genesis","chapters":[["verse 1","verse 2",...],...]},...]}`.

Study Bible (built with `ministry-app/scripts/build-*.py`, downloaded once and kept on the phone):
- `crossrefs.json` cross-references from OpenBible.info (CC BY), based on the Treasury of Scripture Knowledge
- `dictionary.json` Easton's Bible Dictionary (1897, public domain)
- `commentary.json` Matthew Henry's Concise Commentary (public domain)
- `places.json` and `map/` Bible maps: places from OpenBible.info Bible Geocoding Data (CC BY 4.0); coastlines, lakes and rivers from Natural Earth (public domain); Leaflet 1.9.4 (BSD 2-clause)
