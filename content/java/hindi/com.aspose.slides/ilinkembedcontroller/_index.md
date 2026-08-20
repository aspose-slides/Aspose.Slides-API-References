---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /hi/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

ऑब्जेक्ट को सहेजते समय कैसे प्रोसेस किया जाना चाहिए, यह निर्धारित करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determines where object should be stored. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Returns an URL to an external object. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Saves external object. |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

ऑब्जेक्ट को कहाँ संग्रहित किया जाना चाहिए, यह निर्धारित करता है। यह मेथड प्रत्येक ऑब्जेक्ट आईडी के लिए एक बार कॉल किया जाता है। यह सुनिश्चित नहीं किया जा सकता कि दो ऑब्जेक्ट समान डेटा, semanticName और contentType के साथ, लेकिन अलग आईडी के साथ न हों।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | int | ऑब्जेक्ट आईडी। यह आईडी सहेजने के ऑपरेशन-व्यापी अद्वितीय है। |
| entityData | byte[] | ऑब्जेक्ट बाइनरी डेटा। यह पैरामीटर null हो सकता है, यदि ऑब्जेक्ट बाइनरी डेटा अभी तक उत्पन्न नहीं हुआ है। |
| semanticName | java.lang.String | ऑब्जेक्ट के अर्थ का वर्णन करने वाला कुछ छोटा टेक्स्ट। नियंत्रक इसे बाहरी ऑब्जेक्ट के नाम के भाग के रूप में उपयोग कर सकता है, लेकिन नामों को अद्वितीय और केवल अनुमत अक्षरों से बना सुनिश्चित करने की जिम्मेदारी डिस्पैचर की है। |
| contentType | java.lang.String | ऑब्जेक्ट का MIME टाइप। |
| recomendedExtension | java.lang.String | फ़ाइल नाम एक्सटेंशन, इस MIME टाइप के लिए अनुशंसित। |

**रिटर्न:**
int - निर्णय

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

बाहरी ऑब्जेक्ट के लिए एक URL लौटाता है। यह मेथड हमेशा कॉल किया जाता है यदि \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ने [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) लौटाया हो और यदि \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ने [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) लौटाया हो तो भी कॉल किया जा सकता है, लेकिन एम्बेडिंग असंभव है। समान ऑब्जेक्ट आईडी के लिए इसे कई बार कॉल किया जा सकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | int | ऑब्जेक्ट आईडी। यह आईडी सहेजने के ऑपरेशन-व्यापी अद्वितीय है। |
| referrer | int | रेफ़रेंसिंग ऑब्जेक्ट की आईडी या 0, यदि ऑब्जेक्ट रूट डॉक्युमेंट द्वारा रेफ़रेंस किया गया है। इसे सापेक्ष लिंक उत्पन्न करने के लिए उपयोग किया जा सकता है। |

**रिटर्न:**
java.lang.String - बाहरी ऑब्जेक्ट का URL या null यदि इस ऑब्जेक्ट को अनदेखा किया जाना चाहिए।

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

बाहरी ऑब्जेक्ट को सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | int | ऑब्जेक्ट आईडी। यह आईडी सहेजने के ऑपरेशन-व्यापी अद्वितीय है। |
| entityData | byte[] | ऑब्जेक्ट बाइनरी डेटा। यह पैरामीटर null नहीं हो सकता। |