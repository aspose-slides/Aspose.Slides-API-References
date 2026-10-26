---
title: ILinkEmbedController
second_title: Aspose.Slides Android के लिए, Java API संदर्भ के माध्यम से
description: सेविंग के दौरान वस्तु को कैसे प्रोसेस किया जाना चाहिए, यह निर्धारित करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

सेविंग के दौरान वस्तु को कैसे प्रोसेस किया जाना चाहिए, यह निर्धारित करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | निर्धारित करता है कि वस्तु कहाँ संग्रहीत की जानी चाहिए। |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | एक बाहरी वस्तु के URL को लौटाता है। |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | बाहरी वस्तु को सहेजता है। |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

निर्धारित करता है कि वस्तु कहाँ संग्रहीत की जानी चाहिए। यह विधि प्रत्येक वस्तु id के लिये एक बार कॉल की जाती है। यह गारंटी नहीं दी जा सकती कि समान डेटा, semanticName और contentType वाली दो वस्तुएँ अलग-अलग id के साथ मौजूद न हों।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | int | वस्तु id। यह id संपूर्ण सेविंग ऑपरेशन में अद्वितीय है। |
| entityData | byte[] | वस्तु का बाइनरी डेटा। यदि वस्तु का बाइनरी डेटा अभी तक उत्पन्न नहीं हुआ है तो यह पैरामीटर null हो सकता है। |
| semanticName | java.lang.String | वस्तु के अर्थ का वर्णन करने वाला छोटा पाठ। कंट्रोलर इसे बाहरी वस्तु के नाम के भाग के रूप में उपयोग कर सकता है, पर यह डिस्पैचर पर निर्भर है कि नाम अद्वितीय और अनुमत अक्षरों में ही हों। |
| contentType | java.lang.String | वस्तु का MIME प्रकार। |
| recomendedExtension | java.lang.String | इस MIME प्रकार के लिये अनुशंसित फ़ाइल नाम एक्सटेंशन। |

**वापसी:**
int - निर्णय

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

एक बाहरी वस्तु के URL को लौटाता है। यह विधि हमेशा तब कॉल होती है जब \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ने [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) लौटाया हो और यह तब भी कॉल हो सकती है जब \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ने [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) लौटाया हो लेकिन एम्बेडिंग असंभव है। समान वस्तु id के लिये कई बार कॉल की जा सकती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | int | वस्तु id। यह id संपूर्ण सेविंग ऑपरेशन में अद्वितीय है। |
| referrer | int | रेफ़र करने वाली वस्तु का id या 0, यदि वस्तु मूल दस्तावेज़ द्वारा रेफ़र की गई है। सापेक्ष लिंक उत्पन्न करने के लिये उपयोग किया जा सकता है। |

**वापसी:**
java.lang.String - बाहरी वस्तु का URL या null यदि इस वस्तु को अनदेखा करना चाहिए।

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

बाहरी वस्तु को सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | int | वस्तु id। यह id संपूर्ण सेविंग ऑपरेशन में अद्वितीय है। |
| entityData | byte[] | वस्तु का बाइनरी डेटा। यह पैरामीटर null नहीं हो सकता। |