---
title: IDigitalSignatureCollection
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: डॉक्यूमेंट में संलग्न डिजिटल हस्ताक्षरों का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/idigitalsignaturecollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

दस्तावेज़ में संलग्न डिजिटल हस्ताक्षरों का एक संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा हस्ताक्षर लौटाता है। |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | संग्रह के अंत में हस्ताक्षर जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर हस्ताक्षर हटाता है। |
| [clear()](#clear--) | संग्रह से सभी हस्ताक्षर हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


इंडेक्स द्वारा हस्ताक्षर लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```


संग्रह के अंत में हस्ताक्षर जोड़ता है.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | जोड़ने के लिए हस्ताक्षर। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


निर्दिष्ट इंडेक्स पर हस्ताक्षर हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हस्ताक्षर का इंडेक्स जिसे हटाना चाहिए। |

### clear() {#clear--}
```
public abstract void clear()
```


संग्रह से सभी हस्ताक्षर हटाता है।