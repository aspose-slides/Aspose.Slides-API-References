---
title: ICustomXmlPartCollection
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस
description: कस्टम XML भागों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icustomxmlpartcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

कस्टम XML भागों का संग्रह दर्शाता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व को वापस करता है। |
| [add(byte[] xmlData)](#add-byte---) | नया कस्टम XML भाग जोड़ता है। |
| [add(String xmlString)](#add-java.lang.String-) | नया कस्टम XML भाग जोड़ता है। |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | नया कस्टम XML भाग जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर कस्टम XML भाग को हटाता है। |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | संग्रह से एक विशिष्ट वस्तु की पहली घटना को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी आइटम हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व को वापस करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व प्राप्त करने का शून्य-आधारित इंडेक्स। |

**रिटर्न:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्दिष्ट इंडेक्स पर तत्व।

### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

नया कस्टम XML भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlData | byte[] | जोड़ने के लिए नए भाग का xml डेटा। |

**रिटर्न:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्मित कस्टम XML भाग।

### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

नया कस्टम XML भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlString | java.lang.String | जोड़ने के लिए नए भाग की xml स्ट्रिंग। |

**रिटर्न:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्मित कस्टम XML भाग।

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

नया कस्टम XML भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputStream | java.io.InputStream | जोड़ने के लिए नए भाग के xml डेटा वाला inputStream। |

**रिटर्न:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्मित कस्टम XML भाग।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर कस्टम XML भाग को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व हटाने का शून्य-आधारित इंडेक्स। |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

संग्रह से एक विशिष्ट वस्तु की पहली घटना को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | हटाने के लिए कस्टम XML भाग। |

**रिटर्न:**
boolean - true यदि आइटम सफलतापूर्वक हटाया गया; अन्यथा, false.

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी आइटम हटाता है।