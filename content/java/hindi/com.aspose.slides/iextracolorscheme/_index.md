---
title: IExtraColorScheme
second_title: Aspose.Slides for Java API Reference
description: Represents an additional color scheme which can be assigned to a slide.
type: docs
url: /hi/com.aspose.slides/iextracolorscheme/
---```
public interface IExtraColorScheme
```

एक अतिरिक्त रंग योजना को दर्शाता है जिसे एक स्लाइड को सौंपा जा सकता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | Returns a name of this scheme. |
| [getColorScheme()](#getColorScheme--) | Returns a color scheme. |
### getName() {#getName--}
```
public abstract String getName()
```


इस स्कीम का एक नाम लौटाता है। केवल-पढ़ने योग्य String.

**Returns:**
java.lang.String
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


एक रंग योजना लौटाता है। केवल-पढ़ने योग्य [IColorScheme](../../com.aspose.slides/icolorscheme).

**Returns:**
[IColorScheme](../../com.aspose.slides/icolorscheme)