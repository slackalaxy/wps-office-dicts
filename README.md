# WPS Office spellcheck dictionaries

This provides spellcheck dictionaries for [WPS Office](https://www.wps.com/). So far, I have found tutorials about [how to use spell check on WPS Office](https://www.wps.com/academy/how-to-use-the-spell-check-quick-tutorials-1870938/), but no actual dictionaries. So, here they are. The language files are adapted from the [LibreOffice Dictionaries](https://github.com/LibreOffice/dictionaries/) project, you can read about the changes in this [old blog post of mine](https://slackalaxy.com/2021/04/03/wps-office-v11-dictionary/). They have been tested on WPS office for Linux, but my wild guess is they should work on Windows, too. For more information, visit [The Document Foundation Wiki](https://wiki.documentfoundation.org/Development/Dictionaries).


## Installation
Depending on your distribution, the system-wide installation location may differ. For [Slackware](http://www.slackware.com/) Linux, follow these instructions:
* get the folder you need, e.g. en_GB for British English. It contains files `dict.conf`, `main.aff`, `main.dic`
* copy the folder to either place:
   * you user only:  `~/.local/share/Kingsoft/office6/dicts/`
   * system-wide: `/opt/kingsoft/wps-office/office6/dicts/spellcheck/`

Note that for Slackware, this is [available on SBo](https://slackbuilds.org/repository/15.0/office/wps-office-dicts/).

## Version 24.2.4.2
Currently, this is adapted from [libreoffice-24.2.4.2](https://github.com/LibreOffice/dictionaries/releases/tag/libreoffice-24.2.4.2)

## Languages included
```
af_ZA    Afrikaans
an_ES    Aragonese
ar       Arabic
be_BY    Belarusian
bg_BG    Bulgarian
bn_BD    Bengali
bo       Tibetan
br_FR    Breton
bs_BA    Bosnian
ca       Catalan
ckb      Kurdish (Sorani)
cs_CZ    Czech
da_DK    Danish
de_AT    German (Austrian)
de_CH    German (Swiss)
de_DE    German
el_GR    Greek
en_AU    English (Australian)
en_CA    English (Canada)
en_GB    English (Great Britain)
en_ZA    English (South African)
eo       Esperanto
es       Spanish (international)
es_AR    Spanish (Argentina)
es_BO    Spanish (Bolivia)
es_CL    Spanish (Chile)
es_CO    Spanish (Colombia)
es_CR    Spanish (Costa Rica)
es_CU    Spanish (Cuba)
es_DO    Spanish (República Dominicana)
es_EC    Spanish (Ecuador)
es_ES    Spanish (España)
es_GQ    Spanish (Guinea Ecuatorial)
es_GT    Spanish (Guatemala)
es_HN    Spanish (Honduras)
es_MX    Spanish (México)
es_NI    Spanish (Nicaragua)
es_PA    Spanish (Panamá)
es_PE    Spanish (Perú)
es_PH    Spanish (Filipinas)
es_PR    Spanish (Puerto Rico)
es_PY    Spanish (Paraguay)
es_SV    Spanish (El Salvador)
es_US    Spanish (Estados Unidos)
es_UY    Spanish (Uruguay)
es_VE    Spanish (Venezuela)
et_EE    Estonian
fa_IR    Farsi
fr       French
gd_GB    Scottish Gaelic
gl_ES    Galician
gu_IN    Gujarati
gug      Guarani
he_IL    Hebrew
hi_IN    Hindi
hr_HR    Croatian
hu_HU    Hungarian
id_ID    Indonesian
is       Icelandic
it_IT    Italian
kmr_Latn Kurdish (Turkey)
ko_KR    Korean
lo_LA    Lao
lt       Lithuanian
lv_LV    Latvian
mn_MN    Mongolian
ne_NP    Nepali
nl_NL    Netherlands
nb_NO    Norwegian (Bokmål)
nn_NO    Norwegian (Nynorsk)
oc_FR    Occitan
pl_PL    Polish
pt_BR    Brazilian Portuguese
pt_PT    Portuguese
ro_RO    Romanian
ru_RU    Russian
si_LK    Sinhala
sk_SK    Slovak
sl_SI    Slovenian
sq_AL    Albanian
sr       Serbian (Cyrillic)
sr_Latn  Serbian (Latin)
sv_SE    Swedish
sv_FI    Swedish (Finland)
sw_TZ    Swahili
te_IN    Telugu
th_TH    Thai
tr_TR    Turkish
uk_UA    Ukrainian
vi_VN    Vietnamese
```