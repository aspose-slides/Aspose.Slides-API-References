---
title: ISlideText
second_title: Aspose.Slides for Android via Java API Reference
description: स्लाइड से निकाले गए पाठ को दर्शाता है
type: docs
url: /hi/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

स्लाइड से निकाले गए पाठ को दर्शाता है

## विधियाँ

| Method | Description |
| --- | --- |
| [getText()](#getText--) | स्लाइड की आकृतियों पर पाठ |
| [getMasterText()](#getMasterText--) | इस स्लाइड के लिए मास्टर पेज की आकृतियों पर पाठ |
| [getLayoutText()](#getLayoutText--) | इस स्लाइड के लिए लेआउट पेज की आकृतियों पर पाठ |
| [getNotesText()](#getNotesText--) | इस स्लाइड के नोट्स पेज की आकृतियों पर पाठ |
| [getCommentsText()](#getCommentsText--) | स्लाइड टिप्पणियों का पाठ |
### getText() {#getText--}
```
public abstract String getText()
```

स्लाइड की आकृतियों पर पाठ

**वापसी:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

इस स्लाइड के लिए मास्टर पेज की आकृतियों पर पाठ

**वापसी:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

इस स्लाइड के लिए लेआउट पेज की आकृतियों पर पाठ

**वापसी:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

इस स्लाइड के नोट्स पेज की आकृतियों पर पाठ

**वापसी:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

स्लाइड टिप्पणियों का पाठ

--------------------

जब पाठ को Arranged मोड का उपयोग करके निकाला जाता है तो यह फ़ील्ड खाली रहता है।

**वापसी:**
java.lang.String