---
title: ISlideText
second_title: Aspose.Slides for Java API Reference
description: स्लाइड से निकाले गए टेक्स्ट को दर्शाता है
type: docs
url: /hi/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

स्लाइड से निकाले गए टेक्स्ट को दर्शाता है
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getText()](#getText--) | स्लाइड के आकारों पर मौजूद टेक्स्ट |
| [getMasterText()](#getMasterText--) | इस स्लाइड के लिए मास्टर पेज के आकारों पर मौजूद टेक्स्ट |
| [getLayoutText()](#getLayoutText--) | इस स्लाइड के लिए लेआउट पेज के आकारों पर मौजूद टेक्स्ट |
| [getNotesText()](#getNotesText--) | इस स्लाइड के लिए नोट्स पेज के आकारों पर मौजूद टेक्स्ट |
| [getCommentsText()](#getCommentsText--) | स्लाइड टिप्पणियों का टेक्स्ट |
### getText() {#getText--}
```
public abstract String getText()
```

स्लाइड के आकारों पर मौजूद टेक्स्ट

**रिटर्न्स:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

इस स्लाइड के लिए मास्टर पेज के आकारों पर मौजूद टेक्स्ट

**रिटर्न्स:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

इस स्लाइड के लिए लेआउट पेज के आकारों पर मौजूद टेक्स्ट

**रिटर्न्स:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

इस स्लाइड के लिए नोट्स पेज के आकारों पर मौजूद टेक्स्ट

**रिटर्न्स:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

स्लाइड टिप्पणियों का टेक्स्ट

--------------------

यह फ़ील्ड तब ख़ाली रहता है जब टेक्स्ट को Arranged मोड का उपयोग करके निकाला जाता है।

**रिटर्न्स:**
java.lang.String