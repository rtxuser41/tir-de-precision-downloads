# Tir de Précision

## تنزيل Android الرسمي — الإصدار 1.0.6

[**تحميل APK الرسمي**][apk] · [صفحة الإصدارات][releases]

**SHA-256 لملف APK:**

`8b3da2977dd7b1c9de4634e9a23c390ab1ceb673372cb5374e30b7073d177d2f`

### التفعيل والاستخدام

- تتيح النسخة تجربة مجانية بإنشاء بطولة واحدة والاحتفاظ بها؛ لا يمكن حذفها من التطبيق. شراء مفتاح التفعيل مدى الحياة (**500 دج مرة واحدة**) يفتح التطبيق بالكامل، بما في ذلك إنشاء بطولات إضافية؛ لا يوجد اشتراك شهري.
- يلزم اتصال بالإنترنت عند أول تفعيل فقط. رمز التفعيل المكوّن من 16 خانة يُستخدم مرة واحدة ويرتبط بأول جهاز Android يفعّله.
- بعد نجاح التفعيل، يُحفظ إيصال التفعيل بأمان على الجهاز ويعمل التطبيق دون اتصال بالإنترنت.
- تصدير PDF عربي/فرنسي بقالب ملخص من صفحتين وسجل للجولات، وقد تمتد البطولات الطويلة إلى صفحات إضافية، مع خط Amiri العربي.
- لطلب رمز تفعيل أو المساعدة: [تواصل مع المطوّر على WhatsApp][whatsapp].

### الخصوصية والأمان

- بيانات البطولات محفوظة محليًا على هاتفك، ولا تُرسل إلى خدمة التفعيل.
- لا يحتوي هذا الإصدار على إعلانات أو SDK للتحليلات أو التتبع. إذن الشبكة الوحيد هو `INTERNET` ويُستخدم للتفعيل عبر HTTPS؛ ولا يفتح WhatsApp إلا إذا اخترت التواصل.
- يضيف AndroidX إذنًا داخليًا باسم التطبيق ومقيّدًا بتوقيع مماثل لحماية مستقبلات النظام؛ لا يمنح وصولًا إلى بياناتك ولا يحتاج إلى موافقة تفاعلية.
- نزّل التطبيق من هذه الصفحة فقط. ملف APK موقّع بشهادة المطوّر الدائمة؛ بصمة شهادة SHA-256:

  `B7685B438CC97EF90D0388508891EDF7760603B651A3F86B7D07CF18104D040F`

### ملفات التحقق

- [SHA256SUMS][sums]
- [الشهادة العامة][certificate]
- [بيانات مصدر البناء][provenance]
- [حزمة الأدلة الموقعة][evidence]
- [بصمة حزمة الأدلة][evidence-sha]

بعد تنزيل الملفات إلى مجلد واحد، نفّذ `sha256sum -c SHA256SUMS` و`sha256sum -c release-evidence.jar.sha256`، ثم تحقّق من توقيع حزمة الأدلة باستخدام `jarsigner -verify -verbose -certs release-evidence.jar`.

### الترقية إلى الإصدار 1.0.6

يمكن تثبيت الإصدار 1.0.6 كتحديث مباشر فوق الإصدار الرسمي 1.0.5 مع الاحتفاظ بالبيانات والتفعيل. أما نسخة الاختبار 1.0.4 فكانت موقّعة بمفتاح Android مختلف؛ قبل حذفها، صدّر بيانات البطولة إلى ملف JSON من الإعدادات، ثم احذف نسخة الاختبار وثبّت APK الرسمي واستعد النسخة الاحتياطية. قد تحتاج رموز التفعيل المستخدمة على نسخة الاختبار إلى بديل من المطوّر.

---

## Téléchargement Android officiel — version 1.0.6

[**Télécharger l’APK officiel**][apk] · [Page des versions][releases]

**SHA-256 de l’APK :**

`8b3da2977dd7b1c9de4634e9a23c390ab1ceb673372cb5374e30b7073d177d2f`

### Activation et utilisation

- L’essai gratuit permet de créer et conserver un seul tournoi, qui ne peut pas être supprimé dans l’application. L’achat d’un code d’activation à vie (**500 DZD en un seul paiement**) débloque l’application complète, y compris les tournois supplémentaires ; aucun abonnement mensuel.
- Une connexion Internet est nécessaire uniquement lors de l’activation. Le code de 16 caractères est à usage unique et lié au premier appareil Android qui l’active.
- Après activation, le reçu est conservé de manière sécurisée sur l’appareil et l’application fonctionne hors ligne.
- Export PDF arabe/français avec un modèle de résumé sur deux pages et l’historique des manches ; les tournois longs peuvent continuer sur des pages supplémentaires. Police arabe Amiri.
- Pour obtenir un code ou de l’aide : [contacter le développeur sur WhatsApp][whatsapp].

### Confidentialité et sécurité

- Les données des tournois restent sur le téléphone et ne sont pas transmises au service d’activation.
- Cette version ne contient ni publicité, ni SDK d’analyse ou de suivi. L’unique permission réseau est `INTERNET`, utilisée pour l’activation HTTPS ; WhatsApp ne s’ouvre que si vous choisissez de contacter le développeur.
- AndroidX ajoute aussi une permission interne, propre à l’application et limitée aux applications signées avec le même certificat, pour protéger les récepteurs système ; elle ne donne pas accès à vos données et ne demande aucune autorisation interactive.
- Téléchargez l’application uniquement depuis cette page. L’APK est signé avec le certificat permanent du développeur ; empreinte SHA-256 du certificat :

  `B7685B438CC97EF90D0388508891EDF7760603B651A3F86B7D07CF18104D040F`

### Fichiers de vérification

- [SHA256SUMS][sums]
- [Certificat public][certificate]
- [Provenance][provenance]
- [Dossier de preuves signé][evidence]
- [Empreinte du dossier][evidence-sha]

Après avoir téléchargé les fichiers dans un même dossier, exécutez `sha256sum -c SHA256SUMS` et `sha256sum -c release-evidence.jar.sha256`, puis vérifiez la signature du dossier avec `jarsigner -verify -verbose -certs release-evidence.jar`.

### Mise à jour vers la version 1.0.6

La version 1.0.6 peut être installée directement sur la version officielle 1.0.5, sans perdre les données ni l’activation. La version de test 1.0.4 utilisait une autre clé Android ; avant de la désinstaller, exportez les tournois en JSON depuis les paramètres, puis installez l’APK officiel et restaurez la sauvegarde. Les codes utilisés sur la version de test peuvent nécessiter un remplacement auprès du développeur.

[apk]: https://github.com/rtxuser41/tir-de-precision-downloads/releases/latest/download/tir-de-precision-v1.0.6.apk
[releases]: https://github.com/rtxuser41/tir-de-precision-downloads/releases/latest
[sums]: https://github.com/rtxuser41/tir-de-precision-downloads/releases/latest/download/SHA256SUMS
[certificate]: https://github.com/rtxuser41/tir-de-precision-downloads/releases/latest/download/signing-certificate.pem
[provenance]: https://github.com/rtxuser41/tir-de-precision-downloads/releases/latest/download/release-provenance.json
[evidence]: https://github.com/rtxuser41/tir-de-precision-downloads/releases/latest/download/release-evidence.jar
[evidence-sha]: https://github.com/rtxuser41/tir-de-precision-downloads/releases/latest/download/release-evidence.jar.sha256
[whatsapp]: https://wa.me/213660946472
