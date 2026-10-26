---
title: FillFormat
second_title: Aspose.Slides for Android हेतु Java API संदर्भ
description: भरण स्वरूप विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/fillformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

भरण स्वरूप विकल्पों को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | भरण प्रकार को लौटाता है या सेट करता है। |
| [setFillType(byte value)](#setFillType-byte-) | भरण प्रकार को लौटाता है या सेट करता है। |
| [getSolidFillColor()](#getSolidFillColor--) | भरण रंग लौटाता है। |
| [getGradientFormat()](#getGradientFormat--) | ग्रेडिएंट भरण स्वरूप लौटाता है। |
| [getPatternFormat()](#getPatternFormat--) | पैटर्न भरण स्वरूप लौटाता है। |
| [getPictureFillFormat()](#getPictureFillFormat--) | चित्र भरण स्वरूप लौटाता है। |
| [getRotateWithShape()](#getRotateWithShape--) | निर्धारित करता है कि भरण को आकार के साथ घुमा जाना चाहिए या नहीं। |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | निर्धारित करता है कि भरण को आकार के साथ घुमा जाना चाहिए या नहीं। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी भरण स्वरूप डेटा प्राप्त करता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल पढ़ने योग्य long.

**वापसी:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


भरण प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [FillType](../../com.aspose.slides/filltype).

**वापसी:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


भरण प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [FillType](../../com.aspose.slides/filltype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


भरण रंग लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


ग्रेडिएंट भरण स्वरूप लौटाता है। केवल पढ़ने योग्य [IGradientFormat](../../com.aspose.slides/igradientformat).

**वापसी:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


पैटर्न भरण स्वरूप लौटाता है। केवल पढ़ने योग्य [IPatternFormat](../../com.aspose.slides/ipatternformat).

**वापसी:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


चित्र भरण स्वरूप लौटाता है। केवल पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**वापसी:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


निर्धारित करता है कि भरण को आकार के साथ घुमा जाना चाहिए या नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


निर्धारित करता है कि भरण को आकार के साथ घुमा जाना चाहिए या नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


विरासत लागू होने के साथ प्रभावी भरण स्वरूप डेटा प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting shape's effective fill format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IFillFormatEffectiveData effectiveFillFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getFillFormat().getEffective();
>  	System.out.println("Type: " + effectiveFillFormat.getFillType());
>  	switch (effectiveFillFormat.getFillType())
>  	{
>  		case FillType.Solid:
>  			System.out.println("Fill color: " + effectiveFillFormat.getSolidFillColor());
>  			break;
>  		case FillType.Pattern:
>  			System.out.println("Pattern style: " + effectiveFillFormat.getPatternFormat().getPatternStyle());
>  			System.out.println("Fore color: " + effectiveFillFormat.getPatternFormat().getForeColor());
>  			System.out.println("Back color: " + effectiveFillFormat.getPatternFormat().getBackColor());
>  			break;
>  		case FillType.Gradient:
>  			System.out.println("Gradient direction: " + effectiveFillFormat.getGradientFormat().getGradientDirection());
>  			System.out.println("Gradient stops count: " + effectiveFillFormat.getGradientFormat().getGradientStops().size());
>  			break;
>  		case FillType.Picture:
>  			System.out.println("Picture width: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getWidth());
>  			System.out.println("Picture height: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getHeight());
>  			break;
>  	}
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).