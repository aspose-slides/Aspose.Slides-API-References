---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: अपरिवर्तनीय वस्तु जो प्रभावी चित्र गुणों को सम्मिलित करती है।
type: docs
url: /hi/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

अपरिवर्तनीय वस्तु जो प्रभावी चित्र गुणों को सम्मिलित करती है।

--------------------

यह इंटरफ़ेस [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) और [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) का भाग के रूप में उपयोग किया जाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getImage()](#getImage--) | संलग्न छवि को लौटाता है। |
| [getLinkPathLong()](#getLinkPathLong--) | लिंक की गई छवि का URL लौटाता है। |
| [getImageTransform()](#getImageTransform--) | छवि रूपांतरण प्रभावों का संग्रह लौटाता है। |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


संलग्न छवि को लौटाता है। केवल-पढ़ने योग्य [IPPImage](../../com.aspose.slides/ippimage).

**रिटर्न:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


लिंक की गई छवि का URL लौटाता है। केवल-पढ़ने योग्य String.

**रिटर्न:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


छवि रूपांतरण प्रभावों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**रिटर्न:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)