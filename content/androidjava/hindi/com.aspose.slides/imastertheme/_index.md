---
title: IMasterTheme
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक मास्टर थीम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imastertheme/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

एक मास्टर थीम का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | अतिरिक्त रंग योजनाओं का संग्रह लौटाता है। |
| [getName()](#getName--) | एक थीम का नाम लौटाता है। |
| [setName(String value)](#setName-java.lang.String-) | एक थीम का नाम लौटाता है। |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


अतिरिक्त रंग योजनाओं का संग्रह लौटाता है। ये योजनाएँ प्रस्तुति की दिखावट को प्रभावित नहीं करतीं, उन्हें स्लाइड के लिए मुख्य रंग योजना के रूप में चयनित किया जा सकता है। केवल-पढ़ने योग्य [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**वापसी:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


एक थीम का नाम लौटाता है। पढ़ने/लिखने योग्य String.

**वापसी:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


एक थीम का नाम लौटाता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |