---
title: TabCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: टैब्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/tabcollection/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject  
```
public final class TabCollection implements ITabCollection, IDOMObject
```

एक टैब्स का संग्रह दर्शाता है।

## मेथड्स

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्शन में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [add(double position, int align)](#add-double-int-) | कलेक्शन में एक Tab जोड़ता है। |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | कलेक्शन में एक Tab जोड़ता है। |
| [clear()](#clear--) | कलेक्शन से सभी तत्वों को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन के निर्दिष्ट सूचकांक पर तत्व को हटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो TabsEx उदाहरण समान हैं या नहीं। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटरिट करने वाला enumerator लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए एक java iterator लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को कलेक्शन से निर्दिष्ट array में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक synchronization root लौटाता है। |

### size() {#size--}
```
public final int size()
```

कलेक्शन में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पठनीय int.

**रिटर्न:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पठनीय [Tab](../../com.aspose.slides/tab)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[ITab](../../com.aspose.slides/itab)

### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

कलेक्शन में एक Tab जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**रिटर्न:**  
[ITab](../../com.aspose.slides/itab) - जोड़ी गई टैब।

### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

कलेक्शन में एक Tab जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | अंत में जोड़ने के लिए Tab ऑब्जेक्ट। |

**रिटर्न:**  
int - वह सूचकांक जहाँ टैब जोड़ा गया।

### clear() {#clear--}
```
public final void clear()
```

कलेक्शन से सभी तत्वों को हटाता है।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

कलेक्शन के निर्दिष्ट सूचकांक पर तत्व को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित सूचकांक। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पठनीय IDOMObject।

**रिटर्न:**  
com.aspose.slides.IDOMObject

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि दो TabsEx उदाहरण समान हैं या नहीं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए वर्तमान TabsEx के साथ TabsEx। |

**रिटर्न:**  
boolean - **true** यदि निर्दिष्ट TabsEx वर्तमान TabsEx के बराबर है; अन्यथा, **false**।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

कलेक्शन के माध्यम से इटरिट करने वाला enumerator लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - एक IGenericEnumerator जिसे कलेक्शन के माध्यम से इटरिट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

पूरे कलेक्शन के लिए एक java iterator लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - पूरे कलेक्शन के लिए एक java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

कलेक्शन से सभी तत्वों को निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य array। |
| index | int | लक्ष्य array में शुरूआती सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। केवल-पठनीय boolean।

**रिटर्न:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक synchronization root लौटाता है। केवल-पठनीय Object।

**रिटर्न:**  
java.lang.Object