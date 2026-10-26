---
title: ShapeElement class
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapeelement/
---
## ShapeElement क्लास

Represents a part of shape with same outline and fill properties.

The ShapeElement type exposes the following members:

## गुण

| गुण | विवरण |
| :- | :- |
| [`parent_shape`](/slides/python-net/hi/aspose.slides/shapeelement/parent_shape/) | Returns a Shape_PPT for which element was created.<br/>            केवल-पढ़ने योग्य [`Shape`](/slides/python-net/hi/aspose.slides/shape). |
| [`path_points`](/slides/python-net/hi/aspose.slides/shapeelement/path_points/) | तत्व के पथ की ज्यामिति को परिभाषित करने वाले बिंदुओं की एक सरणी प्राप्त करता है। |
| [`path_types`](/slides/python-net/hi/aspose.slides/shapeelement/path_types/) | Gets an array of byte values that specify the type of each point in the element's path. <br/>            <br/>**0**  दर्शाता है कि बिंदु एक आकृति की शुरुआत है।<br/><br/><br/>**1**  दर्शाता है कि बिंदु एक रेखा के दो अंत बिंदुओं में से एक है।<br/><br/><br/>**3**  दर्शाता है कि बिंदु एक क्यूबिक बीज़ियर स्प्लाइन का अंत बिंदु या नियंत्रण बिंदु है।<br/><br/><br/>**7**  तीन निम्न क्रम के बिट्स को छोड़कर सभी बिट्स को मास्क करता है, जो बिंदु प्रकार को दर्शाते हैं।<br/><br/><br/>**16**  निर्दिष्ट करता है कि संबंधित खंड डैश्ड है।<br/><br/><br/>**32**  निर्दिष्ट करता है कि बिंदु एक मार्कर है।<br/><br/><br/>**128**  निर्दिष्ट करता है कि बिंदु एक बंद उपपथ (आकृति) में अंतिम बिंदु है।<br/><br/><br/>**129**  दर्शाता है कि डेटा बिंदु दोनों ही एक रेखा खंड का अंत बिंदु और एक बंद उपपथ का अंतिम बिंदु है। |
| [`fill_source`](/slides/python-net/hi/aspose.slides/shapeelement/fill_source/) | तत्व को कैसे भरना है, इसके बारे में जानकारी लौटाता है।<br/>            केवल-पढ़ने योग्य [`ShapeElementFillSource`](/slides/python-net/hi/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/hi/aspose.slides/shapeelement/stroke_source/) | तत्व को कैसे स्ट्रोक करना है, इसके बारे में जानकारी लौटाता है।<br/>            केवल-पढ़ने योग्य [`ShapeElementStrokeSource`](/slides/python-net/hi/aspose.slides/shapeelementstrokesource). |


### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)