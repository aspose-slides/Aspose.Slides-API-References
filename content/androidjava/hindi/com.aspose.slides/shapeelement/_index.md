---
title: ShapeElement
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस
description: एक ही रूपरेखा और भराव गुणों वाले आकार के एक भाग को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/shapeelement/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

एक ही रूपरेखा और भराव गुणों वाले आकार का एक भाग दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getParentShape()](#getParentShape--) | एक Shape_PPT लौटाता है जिसके लिए तत्व बनाया गया था। |
| [getPathPoints()](#getPathPoints--) | तत्व के पथ की ज्यामिति को परिभाषित करने वाले बिंदुओं की एक सरणी प्राप्त करता है। |
| [getPathTypes()](#getPathTypes--) | तत्व के पथ में प्रत्येक बिंदु के प्रकार को निर्दिष्ट करने वाले बाइट मानों की एक सरणी प्राप्त करता है। |
| [getFillSource()](#getFillSource--) | एक तत्व को भरने के बारे में जानकारी लौटाता है। |
| [getStrokeSource()](#getStrokeSource--) | एक तत्व को स्ट्रोक करने के बारे में जानकारी लौटाता है। |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

एक Shape_PPT लौटाता है जिसके लिए तत्व बनाया गया था। केवल-पढ़ने योग्य [Shape](../../com.aspose.slides/shape).

**वापसी:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

तत्व के पथ की ज्यामिति को परिभाषित करने वाले बिंदुओं की एक सरणी प्राप्त करता है।

**वापसी:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

तत्व के पथ में प्रत्येक बिंदु के प्रकार को निर्दिष्ट करने वाले बाइट मानों की एक सरणी प्राप्त करता है।

**0** दर्शाता है कि बिंदु आकृति की शुरुआत है।

**1** दर्शाता है कि बिंदु रेखा के दो अंत बिंदुओं में से एक है।

**3** दर्शाता है कि बिंदु क्यूबिक बेज़ियर स्प्लाइन का अंत बिंदु या नियंत्रण बिंदु है।

**7** सभी बिट्स को मास्क करता है सिवाय तीन निम्न-क्रम बिटों के, जो बिंदु प्रकार को दर्शाते हैं।

**16** दर्शाता है कि संबंधित खण्ड डैश्ड है।

**32** दर्शाता है कि बिंदु एक मार्कर है।

**128** दर्शाता है कि बिंदु बंद उपपथ (आकृति) में अंतिम बिंदु है।

**129** दर्शाता है कि डेटा बिंदु एक रेखा खंड के अंत बिंदु और बंद उपपथ का अंतिम बिंदु दोनों है।

**वापसी:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

एक तत्व को भरने के बारे में जानकारी लौटाता है। केवल-पढ़ने योग्य [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource)।

**वापसी:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

एक तत्व को स्ट्रोक करने के बारे में जानकारी लौटाता है। केवल-पढ़ने योग्य [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource)।

**वापसी:**
byte