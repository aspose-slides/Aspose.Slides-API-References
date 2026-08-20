---
title: ShapeElement
second_title: Aspose.Slides for Java API संदर्भ
description: एक ही रूपरेखा और भराव गुणों वाले आकार का एक भाग दर्शाता है।
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

इसे समान रूपरेखा और भराव गुणों के साथ आकार का एक भाग दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getParentShape()](#getParentShape--) | एक Shape_PPT लौटाता है जिसके लिए तत्व बनाया गया था। |
| [getPathPoints()](#getPathPoints--) | ऐसे बिंदुओं का एरे प्राप्त करता है जो तत्व के पथ की ज्यामिति को परिभाषित करता है। |
| [getPathTypes()](#getPathTypes--) | ऐसे बाइट मानों का एरे प्राप्त करता है जो तत्व के पथ में प्रत्येक बिंदु के प्रकार को निर्दिष्ट करता है। |
| [getFillSource()](#getFillSource--) | एक तत्व को भरने के तरीके के बारे में जानकारी लौटाता है। |
| [getStrokeSource()](#getStrokeSource--) | एक तत्व को स्ट्रोक करने के तरीके के बारे में जानकारी लौटाता है। |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

एक Shape_PPT लौटाता है जिसके लिए तत्व बनाया गया था। केवल पढ़ने योग्य [Shape](../../com.aspose.slides/shape).

**रिटर्न:**  
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

ऐसे बिंदुओं का एरे प्राप्त करता है जो तत्व के पथ की ज्यामिति को परिभाषित करता है।

**रिटर्न:**  
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

ऐसे बाइट मानों का एरे प्राप्त करता है जो तत्व के पथ में प्रत्येक बिंदु के प्रकार को निर्दिष्ट करता है।

**0** इंगित करता है कि बिंदु एक आकृति की शुरुआत है।

**1** इंगित करता है कि बिंदु एक रेखा के दो अंत बिंदुओं में से एक है।

**3** इंगित करता है कि बिंदु एक क्यूबिक बेज़ियर स्प्लाइन का अंत बिंदु या नियंत्रण बिंदु है।

**7** सभी बिट्स को मास्क करता है सिवाय तीन निम्न क्रम के बिट्स के, जो बिंदु प्रकार को दर्शाते हैं।

**16** निर्दिष्ट करता है कि संबंधित खंड डैश्ड है।

**32** निर्दिष्ट करता है कि बिंदु एक मार्कर है।

**128** निर्दिष्ट करता है कि बिंदु बंद उपपथ (आकृति) में अंतिम बिंदु है।

**129** इंगित करता है कि डेटा बिंदु एक रेखा खंड अंत बिंदु और बंद उपपथ का अंतिम बिंदु दोनों है।

**रिटर्न:**  
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

एक तत्व को भरने के तरीके के बारे में जानकारी लौटाता है। केवल पढ़ने योग्य [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**रिटर्न:**  
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

एक तत्व को स्ट्रोक करने के तरीके के बारे में जानकारी लौटाता है। केवल पढ़ने योग्य [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**रिटर्न:**  
byte