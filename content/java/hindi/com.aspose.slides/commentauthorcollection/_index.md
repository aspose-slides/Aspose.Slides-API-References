---
title: CommentAuthorCollection
second_title: Aspose.Slides for Java API संदर्भ
description: टिप्पणी लेखकों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/commentauthorcollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

टिप्पणी लेखकों के संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में निहित तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | संग्रह के अंत में नया लेखक जोड़ता है। |
| [toArray()](#toArray--) | सभी लेखकों के साथ एक ऐरे बनाता और लौटाता है। |
| [findByName(String name)](#findByName-java.lang.String-) | नाम के द्वारा एक संग्रह में लेखक खोजता है। |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | नाम और प्रथमाक्षर के द्वारा एक संग्रह में लेखक खोजता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह के निर्दिष्ट अनुक्रमांक पर लेखक को हटाता है। |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | संग्रह में निर्दिष्ट लेखक की पहली घटना को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी लेखकों को हटाता है। |
| [iterator()](#iterator--) | एक एन्ह्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटर करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुँच समन्वित (थ्रेड-सेफ़) है। |
| [getSyncRoot()](#getSyncRoot--) | एक समन्वयन मूल लौटाता है। |
### size() {#size--}
```
public final int size()
```

संग्रह में वास्तविक रूप से निहित तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**वापसी:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

संग्रह के अंत में नया लेखक जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | नए लेखक का नाम। |
| initials | java.lang.String | नए लेखक के प्रथमाक्षर। |

**वापसी:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - नया [ICommentAuthor](../../com.aspose.slides/icommentauthor) ऑब्जेक्ट।
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

सभी लेखकों के साथ एक ऐरे बनाता और लौटाता है।

**वापसी:**  
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) की ऐरे
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

नाम के द्वारा एक संग्रह में लेखक खोजता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | ढूँढने वाले लेखक का नाम। |

**वापसी:**  
com.aspose.slides.ICommentAuthor[] - लेखक या null।
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

नाम और प्रथमाक्षर के द्वारा एक संग्रह में लेखक खोजता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | ढूँढने वाले लेखक का नाम। |
| initials | java.lang.String | ढूँढने वाले लेखक के प्रथमाक्षर। |

**वापसी:**  
com.aspose.slides.ICommentAuthor[] - लेखक या null।
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह के निर्दिष्ट अनुक्रमांक पर लेखक को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित अनुक्रमांक। |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

संग्रह में निर्दिष्ट लेखक की पहली घटना को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | संग्रह से हटाने हेतु लेखक। |
### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी लेखकों को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

एक एन्ह्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटर करता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - एक IGenericEnumerator जो संग्रह के माध्यम से इटर करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - पूरे संग्रह के लिए एक java.util.Iterator।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित ऐरे। |
| index | int | लक्षित ऐरे में प्रारंभिक अनुक्रमांक। |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि क्या संग्रह तक पहुँच समन्वित (थ्रेड-सेफ़) है। केवल-पढ़ने योग्य boolean।

**वापसी:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समन्वयन मूल लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**  
java.lang.Object