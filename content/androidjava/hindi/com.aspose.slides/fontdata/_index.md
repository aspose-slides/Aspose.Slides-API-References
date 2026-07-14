---
title: FontData
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक फ़ॉन्ट परिभाषा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/fontdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

फ़ॉन्ट परिभाषा का प्रतिनिधित्व करता है। अपरिवर्तनीय।

## कंस्ट्रक्टर्स

| Constructor | Description |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | निर्दिष्ट फ़ॉन्ट नाम के साथ एक नया FontData ऑब्जेक्ट बनाता है। |

## विधियाँ

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | फ़ॉन्ट नाम वापस देता है। |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | फ़ॉन्ट नाम वापस देता है, थीम संदर्भ को उपयोग किए गए वास्तविक फ़ॉन्ट से बदलते हुए। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो FontData इंस्टेंस समान हैं या नहीं। |
| [hashCode()](#hashCode--) | एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, हैशिंग एल्गोरिदम और हैश तालिका जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त। |
| [toString()](#toString--) | स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```


निर्दिष्ट फ़ॉन्ट नाम के साथ एक नया FontData ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | फ़ॉन्ट नाम। |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


फ़ॉन्ट नाम वापस देता है। पढ़ें/लिखें स्ट्रिंग।

**रिटर्न:**
java.lang.String

### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```


फ़ॉन्ट नाम वापस देता है, थीम संदर्भ को उपयोग किए गए वास्तविक फ़ॉन्ट से बदलते हुए।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | थीम जिससे थीम्ड फ़ॉन्ट नाम लेना चाहिए। यह कॉलर पर निर्भर है कि वह सही मान प्रदान करे। देखें [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**रिटर्न:**
java.lang.String - फ़ॉन्ट नाम।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि दो FontData इंस्टेंस समान हैं या नहीं।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | |
| obj | java.lang.Object | वर्तमान FontData के साथ तुलना करने हेतु FontData। |

**रिटर्न:**
boolean - **true** यदि निर्दिष्ट FontData वर्तमान FontData के बराबर है; अन्यथा, **false**।

### hashCode() {#hashCode--}
```
public int hashCode()
```


एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, हैशिंग एल्गोरिदम और हैश तालिका जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त।

**रिटर्न:**
int - FontData का हैश कोड।

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग प्रतिनिधित्व लौटाता है।

**रिटर्न:**
java.lang.String - स्ट्रिंग प्रतिनिधित्व।