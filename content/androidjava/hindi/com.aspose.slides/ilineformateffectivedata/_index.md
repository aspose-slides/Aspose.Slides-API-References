---
title: ILineFormatEffectiveData
second_title: Aspose.Slides for Android द्वारा Java API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो प्रभावी लाइन फ़ॉर्मेटिंग गुणों को सम्मिलित करती है।
type: docs
url: /hi/com.aspose.slides/ilineformateffectivedata/
---
**सभी लागू इंटरफेस:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

इम्यूटेबल ऑब्जेक्ट जो प्रभावी लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ को समाहित करता है।

--------------------

यह इंटरफ़ेस [ILineFormat](../../com.aspose.slides/ilineformat) इंटरफ़ेस के साथ मिलकर प्रयुक्त होता है ताकि विरासत लागू होने पर प्रभावी फ़ॉर्मेटिंग मान लौटाए जा सकें।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | एक रेखा का भराव फ़ॉर्मेट लौटाता है। |
| [getSketchFormat()](#getSketchFormat--) | एक रेखा का स्केच फ़ॉर्मेट लौटाता है। |
| [getWidth()](#getWidth--) | एक रेखा की चौड़ाई लौटाता है। |
| [getDashStyle()](#getDashStyle--) | रेखा की डैश शैली लौटाता है। |
| [getCustomDashPattern()](#getCustomDashPattern--) | कस्टम डैश पैटर्न लौटाता है। |
| [getCapStyle()](#getCapStyle--) | रेखा के कैप शैली लौटाता है। |
| [getStyle()](#getStyle--) | रेखा की शैली लौटाता है। |
| [getAlignment()](#getAlignment--) | रेखा का संरेखण लौटाता है। |
| [getJoinStyle()](#getJoinStyle--) | रेखाओं के जुड़ाव शैली लौटाता है। |
| [getMiterLimit()](#getMiterLimit--) | एक रेखा की मिटर सीमा लौटाता है। |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | एक रेखा की शुरुआत में तीर के सिर की शैली लौटाता है। |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | एक रेखा के अंत में तीर के सिर की शैली लौटाता है। |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | एक रेखा की शुरुआत में तीर के सिर की चौड़ाई लौटाता है। |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | एक रेखा के अंत में तीर के सिर की चौड़ाई लौटाता है। |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | एक रेखा की शुरुआत में तीर के सिर की लंबाई लौटाता है। |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | एक रेखा के अंत में तीर के सिर की लंबाई लौटाता है। |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | निर्धारित करता है कि दो ILineFormatEffectiveData ऑब्जेक्ट समान हैं या नहीं। |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

एक रेखा का भराव फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**वापसी:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

एक रेखा का स्केच फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**वापसी:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

एक रेखा की चौड़ाई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

रेखा की डैश शैली लौटाता है। केवल-पढ़ने योग्य [LineDashStyle](../../com.aspose.slides/linedashstyle).

**वापसी:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

कस्टम डैश पैटर्न लौटाता है। केवल-पढ़ने योग्य float[].

**वापसी:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

रेखा के कैप शैली लौटाता है। केवल-पढ़ने योग्य [LineCapStyle](../../com.aspose.slides/linecapstyle).

**वापसी:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

रेखा की शैली लौटाता है। केवल-पढ़ने योग्य [LineStyle](../../com.aspose.slides/linestyle).

**वापसी:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

रेखा का संरेखण लौटाता है। केवल-पढ़ने योग्य [LineAlignment](../../com.aspose.slides/linealignment).

**वापसी:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

रेखाओं के जुड़ाव शैली लौटाता है। केवल-पढ़ने योग्य [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**वापसी:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

मिटर सीमा लौटाता है। केवल-पढ़ने योग्य float.

**वापसी:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

एक रेखा की शुरुआत में तीर के सिर की शैली लौटाता है। केवल-पढ़ने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**वापसी:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

एक रेखा के अंत में तीर के सिर की शैली लौटाता है। केवल-पढ़ने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**वापसी:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

एक रेखा की शुरुआत में तीर के सिर की चौड़ाई लौटाता है। केवल-पढ़ने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**वापसी:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

एक रेखा के अंत में तीर के सिर की चौड़ाई लौटाता है। केवल-पढ़ने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**वापसी:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

एक रेखा की शुरुआत में तीर के सिर की लंबाई लौटाता है। केवल-पढ़ने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**वापसी:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

एक रेखा के अंत में तीर के सिर की लंबाई लौटाता है। केवल-पढ़ने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**वापसी:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

निर्धारित करता है कि दो ILineFormatEffectiveData ऑब्जेक्ट समान हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | वर्तमान ILineFormatEffectiveData के साथ तुलना करने के लिए ILineFormatEffectiveData। |

**वापसी:**
boolean - **true** यदि निर्दिष्ट ILineFormatEffectiveData वर्तमान ILineFormatEffectiveData के बराबर है; अन्यथा, **false**.