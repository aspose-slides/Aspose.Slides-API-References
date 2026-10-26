---
title: FontSubstitutionInfo
second_title: Aspose.Slides Android के लिए जावा API संदर्भ के माध्यम से
description: यह संरचना फ़ॉन्ट प्रतिस्थापन के बारे में जानकारी का प्रतिनिधित्व करती है जब इसे रेंडर किया जाएगा।
type: docs
url: /hi/com.aspose.slides/fontsubstitutioninfo/
---
**विरासत:**
java.lang.Object
```
public class FontSubstitutionInfo
```

यह संरचना फ़ॉन्ट प्रतिस्थापन के बारे में जानकारी का प्रतिनिधित्व करती है जब इसे रेंडर किया जाएगा।

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
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) क्लास का एक उदाहरण बनाता है। |
## मेथड

| मेथड | विवरण |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | प्रस्तुति में स्रोत फ़ॉन्ट नाम इंगित करता है। |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | मूल फ़ॉन्ट के लिए प्रतिस्थापन फ़ॉन्ट नाम इंगित करता है। |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


[FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) क्लास का एक उदाहरण बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| originFontName | java.lang.String | प्रस्तुति में स्रोत फ़ॉन्ट नाम स्ट्रिंग |
| substFontName | java.lang.String | मूल फ़ॉन्ट के लिए प्रतिस्थापन फ़ॉन्ट नाम स्ट्रिंग |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


प्रस्तुति में स्रोत फ़ॉन्ट नाम इंगित करता है। केवल-पढ़ने योग्य स्ट्रिंग

**वापसी:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


मूल फ़ॉन्ट के लिए प्रतिस्थापन फ़ॉन्ट नाम इंगित करता है। केवल-पढ़ने योग्य स्ट्रिंग

**वापसी:**
java.lang.String