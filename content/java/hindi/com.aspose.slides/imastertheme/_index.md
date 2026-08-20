---
title: IMasterTheme
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक मास्टर थीम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imastertheme/
---
**सभी लागू इंटरफेसेस:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

एक मास्टर थीम का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Returns the collection of additional color schemes. |
| [getName()](#getName--) | Returns the name of a theme. |
| [setName(String value)](#setName-java.lang.String-) | Returns the name of a theme. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

अतिरिक्त रंग योजनाओं का संग्रह लौटाता है। ये योजनाएँ प्रस्तुति के रूप को प्रभावित नहीं करतीं, इन्हें स्लाइड के लिए प्रमुख रंग योजना के रूप में चुना जा सकता है। केवल-पढ़ने योग्य [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)।

**वापसी:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

एक थीम का नाम लौटाता है। पढ़ने/लिखने योग्य String।

**वापसी:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

एक थीम का नाम लौटाता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |