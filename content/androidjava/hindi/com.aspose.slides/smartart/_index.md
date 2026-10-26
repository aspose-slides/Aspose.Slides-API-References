---
title: SmartArt
second_title: Aspose.Slides for Android जावा API रेफ़रेंस के माध्यम से
description: एक SmartArt आरेख का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/smartart/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

SmartArt आरेख का प्रतिनिधित्व करता है
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | SmartArt ऑब्जेक्ट में सभी नोड्स का संग्रह लौटाता है। |
| [getNodes()](#getNodes--) | SmartArt ऑब्जेक्ट में रूट नोड्स का संग्रह लौटाता है। |
| [getLayout()](#getLayout--) | SmartArt ऑब्जेक्ट का लेआउट लौटाता है या सेट करता है। |
| [setLayout(int value)](#setLayout-int-) | SmartArt ऑब्जेक्ट का लेआउट लौटाता है या सेट करता है। |
| [getQuickStyle()](#getQuickStyle--) | SmartArt ऑब्जेक्ट की त्वरित शैली लौटाता है या सेट करता है। |
| [setQuickStyle(int value)](#setQuickStyle-int-) | SmartArt ऑब्जेक्ट की त्वरित शैली लौटाता है या सेट करता है। |
| [getColorStyle()](#getColorStyle--) | SmartArt ऑब्जेक्ट की रंग शैली लौटाता है या सेट करता है। |
| [setColorStyle(int value)](#setColorStyle-int-) | SmartArt ऑब्जेक्ट की रंग शैली लौटाता है या सेट करता है। |
| [isReversed()](#isReversed--) | डायग्राम यदि उलटने का समर्थन करता है, तो (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में SmartArt आरेख की स्थिति लौटाता है या सेट करता है। |
| [setReversed(boolean value)](#setReversed-boolean-) | डायग्राम यदि उलटने का समर्थन करता है, तो (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में SmartArt आरेख की स्थिति लौटाता है या सेट करता है। |
### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```

SmartArt ऑब्जेक्ट में सभी नोड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**वापसी:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```

SmartArt ऑब्जेक्ट में रूट नोड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**वापसी:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public final int getLayout()
```

SmartArt ऑब्जेक्ट का लेआउट लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**वापसी:**
int
### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```

SmartArt ऑब्जेक्ट का लेआउट लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```

SmartArt ऑब्जेक्ट की त्वरित शैली लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**वापसी:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```

SmartArt ऑब्जेक्ट की त्वरित शैली लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```

SmartArt ऑब्जेक्ट की रंग शैली लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**वापसी:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```

SmartArt ऑब्जेक्ट की रंग शैली लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public final boolean isReversed()
```

डायग्राम यदि उलटने का समर्थन करता है, तो (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में SmartArt आरेख की स्थिति लौटाता है या सेट करता है। पढ़ें/लिखें  boolean .

**वापसी:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```

डायग्राम यदि उलटने का समर्थन करता है, तो (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में SmartArt आरेख की स्थिति लौटाता है या सेट करता है। पढ़ें/लिखें  boolean .

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |