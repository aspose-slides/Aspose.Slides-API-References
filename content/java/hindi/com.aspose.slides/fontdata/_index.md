---
title: FontData
second_title: Aspose.Slides for Java API संदर्भ
description: फ़ॉन्ट परिभाषा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/fontdata/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

फ़ॉन्ट परिभाषा को दर्शाता है। अपरिवर्तनीय।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | निर्दिष्ट फ़ॉन्ट नाम के साथ एक नया FontData ऑब्जेक्ट बनाता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFontName()](#getFontName--) | फ़ॉन्ट नाम लौटाता है। |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | फ़ॉन्ट नाम लौटाता है, थीम रेफ़रेंस को वास्तविक प्रयुक्त फ़ॉन्ट से बदलते हुए। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो FontData इंस्टेंस समान हैं या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश तालिका जैसे डेटा स्ट्रक्चर में उपयोगी है। |
| [toString()](#toString--) | स्ट्रिंग प्रतिनिधित्व लौटाता है। |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```


निर्दिष्ट फ़ॉन्ट नाम के साथ एक नया FontData ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | फ़ॉन्ट नाम। |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


फ़ॉन्ट नाम लौटाता है। पढ़ने/लिखने योग्य String।

**रिटर्न मान:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```


फ़ॉन्ट नाम लौटाता है, थीम रेफ़रेंस को वास्तविक प्रयुक्त फ़ॉन्ट से बदलते हुए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | थीम जिससे थीम्ड फ़ॉन्ट नाम लिया जाना चाहिए। यह कॉलर पर निर्भर है कि सही मान प्रदान करे। देखें [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**रिटर्न मान:**
java.lang.String - फ़ॉन्ट नाम।
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि दो FontData इंस्टेंस समान हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | वर्तमान FontData के साथ तुलना करने के लिए FontData। |

**रिटर्न मान:**
boolean - **true** यदि निर्दिष्ट FontData वर्तमान FontData के बराबर है; अन्यथा, **false**।
### hashCode() {#hashCode--}
```
public int hashCode()
```


किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश तालिका जैसे डेटा स्ट्रक्चर में उपयोगी है।

**रिटर्न मान:**
int - FontData का हैश कोड।
### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग प्रतिनिधित्व लौटाता है।

**रिटर्न मान:**
java.lang.String - String प्रतिनिधित्व।