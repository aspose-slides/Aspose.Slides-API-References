---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Java API संदर्भ
description: अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी अनुच्छेद बुलेट फ़ॉर्मेटिंग गुणों को शामिल करता है।
type: docs
url: /hi/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी अनुच्छेद बुलेट फ़ॉर्मेटिंग गुणों को शामिल करता है।

--------------------

यह इंटरफ़ेस [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) का हिस्सा के रूप में उपयोग किया जाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | एक पैराग्राफ का बुलेट प्रकार लौटाता है। |
| [getChar()](#getChar--) | एक पैराग्राफ का बुलेट वर्ण लौटाता है। |
| [getActualBulletValue()](#getActualBulletValue--) | पैरेंट पैराग्राफ के लिये वास्तविक बुलेट मान लौटाता है। |
| [getFont()](#getFont--) | एक पैराग्राफ का बुलेट फ़ॉन्ट लौटाता है। |
| [getHeight()](#getHeight--) | एक पैराग्राफ का बुलेट ऊँचाई लौटाता है। |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | क्रमांकित बुलेट समूह के लिये प्रयुक्त पहला संख्या लौटाता है। |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | क्रमांकित बुलेट की शैली लौटाता है। |
| [isBulletHardColor()](#isBulletHardColor--) | निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले भाग से विरासत में लेता है। |
| [isBulletHardFont()](#isBulletHardFont--) | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले भाग से विरासत में लेता है। |
| [getPicture()](#getPicture--) | पैराग्राफ में बुलेट के रूप में प्रयुक्त चित्र लौटाता है। |
| [getFillFormat()](#getFillFormat--) | एक पैराग्राफ का बुलेट फ़िल फ़ॉर्मेट लौटाता है। |

### getType() {#getType--}
```
public abstract byte getType()
```

एक पैराग्राफ का बुलेट प्रकार लौटाता है। केवल-रीड [BulletType](../../com.aspose.slides/bullettype).

**Returns:**
byte

### getChar() {#getChar--}
```
public abstract char getChar()
```

एक पैराग्राफ का बुलेट वर्ण लौटाता है। केवल-रीड char.

**Returns:**
char

### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

पैरेंट पैराग्राफ के लिये वास्तविक बुलेट मान लौटाता है। केवल-रीड String.

**Returns:**
java.lang.String

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

एक पैराग्राफ का बुलेट फ़ॉन्ट लौटाता है। केवल-रीड [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

एक पैराग्राफ का बुलेट ऊँचाई लौटाता है। केवल-रीड float.

**Returns:**
float

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

क्रमांकित बुलेट समूह के लिये प्रयुक्त पहला संख्या लौटाता है। केवल-रीड short.

**Returns:**
short

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

क्रमांकित बुलेट की शैली लौटाता है। केवल-रीड [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Returns:**
byte

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले भाग से विरासत में लेता है। यदि बुलेट का अपना रंग है तो **true** लौटाता है और यदि बुलेट पहला भाग से रंग विरासत में लेता है तो **false** लौटाता है। केवल-रीड boolean.

**Returns:**
boolean

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले भाग से विरासत में लेता है। यदि बुलेट का अपना फ़ॉन्ट है तो **true** लौटाता है और यदि बुलेट पहला भाग से फ़ॉन्ट विरासत में लेता है तो **true** लौटाता है। केवल-रीड boolean.

**Returns:**
boolean

### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

पैराग्राफ में बुलेट के रूप में प्रयुक्त चित्र लौटाता है। केवल-रीड [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Returns:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

एक पैराग्राफ का बुलेट फ़िल फ़ॉर्मेट लौटाता है। केवल-रीड [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // मान लीजिए कि पहली स्लाइड के पहले शेप को ऑटोशेप है जिसमें कुछ टेक्स्ट है...
>      // टेक्स्ट पैराग्राफ़ के बुलेट्स की जानकारी आउटपुट करें
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)