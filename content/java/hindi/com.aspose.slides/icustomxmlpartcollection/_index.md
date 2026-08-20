---
title: ICustomXmlPartCollection
second_title: Aspose.Slides for Java API संदर्भ
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

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व लौटाता है। |
| [add(byte[] xmlData)](#add-byte---) | नया कस्टम XML भाग जोड़ता है। |
| [add(String xmlString)](#add-java.lang.String-) | नया कस्टम XML भाग जोड़ता है। |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | नया कस्टम XML भाग जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर कस्टम XML भाग हटाता है। |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | संग्रह से विशिष्ट वस्तु की पहली उपस्थिति हटाता है। |
| [clear()](#clear--) | संग्रह से सभी वस्तुएँ हटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व प्राप्त करने के लिए शून्य-आधारित सूचकांक। |

**वापसी मान:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - निर्दिष्ट सूचकांक पर तत्व।

### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

नया कस्टम XML भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlData | byte[] | जोड़े जाने वाले नए भाग का XML डेटा। |

**वापसी मान:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - बनाया गया कस्टम XML भाग।

### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

नया कस्टम XML भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlString | java.lang.String | जोड़े जाने वाले नए भाग की XML स्ट्रिंग। |

**वापसी मान:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - बनाया गया कस्टम XML भाग।

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

नया कस्टम XML भाग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputStream | java.io.InputStream | जोड़े जाने वाले नए भाग के XML डेटा वाला इनपुट स्ट्रीम। |

**वापसी मान:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - बनाया गया कस्टम XML भाग।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट सूचकांक पर कस्टम XML भाग हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित सूचकांक। |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

संग्रह से विशिष्ट वस्तु की पहली उपस्थिति हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | हटाए जाने वाला कस्टम XML भाग। |

**वापसी मान:**
boolean - true यदि वस्तु सफलतापूर्वक हटाई गई; अन्यथा, false।

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी वस्तुएँ हटाता है।