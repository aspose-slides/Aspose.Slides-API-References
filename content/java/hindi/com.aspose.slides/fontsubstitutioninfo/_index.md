---
title: FontSubstitutionInfo
second_title: Aspose.Slides for Java API संदर्भ
description: यह संरचना फ़ॉन्ट प्रतिस्थापन के बारे में जानकारी दर्शाती है जब इसे रेंडर किया जाएगा।
type: docs
url: /hi/com.aspose.slides/fontsubstitutioninfo/
---
**विरासत:**
java.lang.Object
```
public class FontSubstitutionInfo
```

यह संरचना फ़ॉन्ट प्रतिस्थापन के बारे में जानकारी दर्शाती है जब इसे रेंडर किया जाएगा।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) क्लास का एक इंस्टेंस बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | प्रेज़ेंटेशन में स्रोत फ़ॉन्ट नाम दर्शाता है। |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | मूल फ़ॉन्ट के लिए प्रतिस्थापन फ़ॉन्ट नाम दर्शाता है। |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

[FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) क्लास का एक इंस्टेंस बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| originFontName | java.lang.String | प्रेज़ेंटेशन में स्रोत फ़ॉन्ट नाम String |
| substFontName | java.lang.String | मूल फ़ॉन्ट के लिए प्रतिस्थापन फ़ॉन्ट नाम String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

प्रेज़ेंटेशन में स्रोत फ़ॉन्ट नाम दर्शाता है। केवल-पढ़ने योग्य String

**रिटर्न:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

मूल फ़ॉन्ट के लिए प्रतिस्थापन फ़ॉन्ट नाम दर्शाता है। केवल-पढ़ने योग्य String

**रिटर्न:**
java.lang.String