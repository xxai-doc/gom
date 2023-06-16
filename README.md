<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

पयली nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) प्रतिष्ठापीत करपाची शिफारस केल्या, आनी मागीर निर्देशिका दाखयल्या उपरांत `direnv allow` ( निर्देशिका प्रवेश केल्या उपरांत [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) आपोआप कार्यान्वीत जातलो).

अर्थ असो: चीनी अणकार जपानी, कोरियन, इंग्लीश, इंग्लीश अणकार हेर सगळ्या भाशांनी. तुमकां फकत चीनी आनी इंग्लीशीक तेंको दिवपाचो आसल्यार तुमी फकत `zh: en` बरोवंक शकतात.

अर्थ असो: चीनी अणकार जपानी, कोरियन, इंग्लीश, इंग्लीश अणकार हेर सगळ्या भाशांनी. तुमकां फकत चीनी आनी इंग्लीशीक तेंको दिवपाचो आसल्यार तुमी फकत `zh: en` बरोवंक शकतात.

* [फ्रंट-एंड कोड](https://github.com/xxai-art/web)
* [एकंदर साइट खातीर भास पॅक](https://github.com/xxai-art/web/tree/main/i18n)
* [लॉगीन मॉड्यूलां खातीर भास पॅक](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [वेबसायट बहुभाषी दस्तावेजीकरण](https://github.com/xxai-doc)

फ्रंट-एंड प्रोग्रामिंग भास [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) आसा, जी coffeescript वाक्यरचनेचेर आदारीत कांय वैशिश्ट्यां जोडटा, पळयात [./coffee_plus.md](./coffee_plus.md) .

## संकेतथळां आनी दस्तावेजांचें आंतरराष्ट्रीयकरण

सकयल दिल्ल्या 3 प्रकल्पांचेर उबारप

* [@ w5 / mdt हांणी केला](https://www.npmjs.com/package/@w5/mdt)

  प्रत्यय `.mdt` आसा, तुमी भायल्या फायलींचो संदर्भ दिवपाक `<+ ./coffee_plus/import.js>` सारको वाक्यरचना वापरूं येता, आनी `.md` प्रत्यया वांगडा मार्कडावन तयार करूंक शकतात.

* [@w5/trmd हांणी केला](https://www.npmjs.com/package/@w5/trmd)

  मार्कडावन अणकार कोड आनी दुवे अणकारीत करचो ना, आनी अणकारीत वाक्य कॅश करतलो. अणकारांत बदल केल्यार पूण मूळ मजकूरांत बदल जावंक ना जाल्यार, तो परतून चालीक लावप अणकारांत बदल परतून बरयचो ना.

* [@ w5/i18n हांणी केला](https://www.npmjs.com/package/@w5/i18n)

  `yaml` तयार केल्ल्या संकेतथळांचो अणकार करपाखातीर भास फायली.

### दस्तावेज अणकार ऑटोमेशन सुचोवण्यो

कोड रिपॉझिटरी पळयात [xxai-art/doc](https://github.com/xxai-art/doc)

पयली nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) प्रतिष्ठापीत करपाची शिफारस केल्या, आनी मागीर निर्देशिका दाखयल्या उपरांत `direnv allow` ( निर्देशिका प्रवेश केल्या उपरांत [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) आपोआप कार्यान्वीत जातलो).

शेंकड्यांनी भाशांनी अणकारीत केल्लो व्हडलो कोड बेस टाळपा खातीर हांवें दरेक भाशे खातीर वेगळो कोड बेस तयार केलो आनी कोड बेस सांठोवपा खातीर एक संघटना तयार केली

वातावरण चडांत चड `GITHUB_ACCESS_TOKEN` सेट केल्यार आनी मागीर [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) चालीक लावप आपोआप कोड रिपॉझिटरी तयार करतले.

अर्थांत, तुमी ताका कोड बेसांतय घालूंक शकतात.

अणकार लिपी संदर्भ [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

लिपी संहितेचो अर्थ असो जाता: १.

[bunx](https://bun.sh/docs/cli/bunx) हें npx च्या बदलाक आसा, जें चड वेगान आसा. अर्थांत, तुमचे कडेन bun स्थापीत ना जाल्यार, तुमी ताचे बदला `npx` वापरूं येता.

`bunx mdt zh` zh निर्देशिकेंत `.mdt` `.md` म्हणून रेंडर करता, सकयल दिल्ल्यो 2 दुवो फायली पळयात

* [कॉफी_प्लस.एमडीटी](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [कॉफी_प्लस.एमडी](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` हो अणकाराक मुळावो कोड आसा (तुमचे कडेन फकत `nodejs` स्थापीत केल्यार, पूण `bun` आनी `direnv` स्थापीत केल्ले नात जाल्यार, तुमी अणकार करपाक `npx i18n` लेगीत चालीक लावंक शकतात).

तो [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) विश्लेशण करतलो , ह्या दस्तावेजांतल्या `i18n.yml` ची संरचना अशी आसा:

```
en:
zh: ja ko en
```

अर्थ असो: चीनी अणकार जपानी, कोरियन, इंग्लीश, इंग्लीश अणकार हेर सगळ्या भाशांनी. तुमकां फकत चीनी आनी इंग्लीशीक तेंको दिवपाचो आसल्यार तुमी फकत `zh: en` बरोवंक शकतात.

निमाणें [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , जें दरेक भाशेच्या `README.md` च्या मुखेल शीर्षक आनी पयल्या उपशीर्षका मदली सामुग्री काडून `README.md` नोंद तयार करता. कोड सामको सोपो आसा, तुमी स्वता पळोवंक शकतात.

फुकट अणकाराक गूगल एपीआय वापरतात. तुमकां Google ऍक्सॅस करूंक मेळना जाल्यार, उपकार करून प्रॉक्सी संरचीत करात आनी सेट करात, जशे की:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

अणकार स्क्रिप्ट `.i18n` निर्देशिकेंत अणकारीत कॅशे तयार करतली, उपकार करून ती `git status` सयत तपासात आनी परत परत अणकार टाळपाखातीर कोड रिपॉझिटरींत जोडात.

उपकार करून दर खेपे तुमी कॅशे अद्ययावत करपाक अणकारांत बदल करतना `bunx i18n` चालीक लावचो.

मूळ मजकूर आनी अणकार एकाच वेळार बदलल्यार, कॅशे गोंदळ जातलो, देखून तुमकां बदल करपाचो आसल्यार, तुमी फकत एक बदलूं येता, आनी मागीर कॅशे अद्ययावत करपाक `bunx i18n` चालीक लावचो.
