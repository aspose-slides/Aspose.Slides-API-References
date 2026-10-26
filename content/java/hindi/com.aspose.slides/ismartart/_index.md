---
title: ISmartArt
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक SmartArt आरेख का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ismartart/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

एक SmartArt आरेख का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | SmartArt ऑब्जेक्ट में सभी नोड्स के संग्रह को लौटाता है। |
| [getNodes()](#getNodes--) | SmartArt ऑब्जेक्ट में मूल नोड्स के संग्रह को लौटाता है। |
| [getLayout()](#getLayout--) | SmartArt ऑब्जेक्ट का लेआउट लौटाता है या सेट करता है। |
| [setLayout(int value)](#setLayout-int-) | SmartArt ऑब्जेक्ट का लेआउट लौटाता है या सेट करता है। |
| [getQuickStyle()](#getQuickStyle--) | SmartArt ऑब्जेक्ट की quick style को लौटाता है या सेट करता है। |
| [setQuickStyle(int value)](#setQuickStyle-int-) | SmartArt ऑब्जेक्ट की quick style को लौटाता है या सेट करता है। |
| [getColorStyle()](#getColorStyle--) | SmartArt ऑब्जेक्ट की color style को लौटाता है या सेट करता है। |
| [setColorStyle(int value)](#setColorStyle-int-) | SmartArt ऑब्जेक्ट की color style को लौटाता है या सेट करता है। |
| [isReversed()](#isReversed--) | यदि आरेख उलटना समर्थन करता है तो SmartArt आरेख की स्थिति (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में लौटाता है या सेट करता है। |
| [setReversed(boolean value)](#setReversed-boolean-) | यदि आरेख उलटना समर्थन करता है तो SmartArt आरेख की स्थिति (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में लौटाता है या सेट करता है। |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


SmartArt ऑब्जेक्ट में सभी नोड्स के संग्रह को लौटाता है। केवल पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)।

**रिटर्न:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


SmartArt ऑब्जेक्ट में मूल नोड्स के संग्रह को लौटाता है। केवल पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)।

**रिटर्न:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


SmartArt ऑब्जेक्ट का लेआउट लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)।

**रिटर्न:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


SmartArt ऑब्जेक्ट का लेआउट लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


SmartArt ऑब्जेक्ट की quick style को लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)।

**रिटर्न:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


SmartArt ऑब्जेक्ट की quick style को लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


SmartArt ऑब्जेक्ट की color style को लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtColorType](../../com.aspose.slides/smartartcolortype)।

**रिटर्न:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


SmartArt ऑब्जेक्ट की color style को लौटाता है या सेट करता है। पढ़ें/लिखें [SmartArtColorType](../../com.aspose.slides/smartartcolortype)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


यदि आरेख उलटना समर्थन करता है तो SmartArt आरेख की स्थिति (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में लौटाता है या सेट करता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


यदि आरेख उलटना समर्थन करता है तो SmartArt आरेख की स्थिति (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में लौटाता है या सेट करता है। पढ़ें/लिखें boolean।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |