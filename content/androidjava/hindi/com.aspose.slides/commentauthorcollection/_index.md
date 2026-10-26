---
title: CommentAuthorCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: टिप्पणी लेखकों के संग्रह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/commentauthorcollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)  
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

टिप्पणी लेखकों का एक संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | संग्रह के अंत में नया लेखक जोड़ता है। |
| [toArray()](#toArray--) | सभी लेखकों के साथ एक एरे बनाता और लौटाता है। |
| [findByName(String name)](#findByName-java.lang.String-) | नाम द्वारा संग्रह में लेखक खोजता है। |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | नाम और प्रारंभिकाक्षर द्वारा संग्रह में लेखक खोजता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट सूचकांक पर लेखक हटाता है। |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | संग्रह में निर्दिष्ट लेखक की पहली उपस्थिति हटाता है। |
| [clear()](#clear--) | संग्रह से सभी लेखकों को हटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरैट करने वाला एक enumerator लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java iterator लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मूल्य लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक synchronization root लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने-योग्य int.

**वापसी:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने-योग्य [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**पैरामीटर** | **प्रकार** | **विवरण** |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

संग्रह के अंत में नया लेखक जोड़ता है।

**पैरामीटर** | **प्रकार** | **विवरण** |
| --- | --- | --- |
| name | java.lang.String | नए लेखक का नाम। |
| initials | java.lang.String | नए लेखक के प्रारंभिकाक्षर। |

**वापसी:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - नया [ICommentAuthor](../../com.aspose.slides/icommentauthor) ऑब्जेक्ट।

### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

सभी लेखकों के साथ एक एरे बनाता और लौटाता है।

**वापसी:**  
com.aspose.slides.ICommentAuthor[] - एरे ऑफ [ICommentAuthor](../../com.aspose.slides/icommentauthor)

### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

नाम द्वारा संग्रह में लेखक खोजता है।

**पैरामीटर** | **प्रकार** | **विवरण** |
| --- | --- | --- |
| name | java.lang.String | खोजने के लिए लेखक का नाम। |

**वापसी:**  
com.aspose.slides.ICommentAuthor[] - लेखक या null.

### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

नाम और प्रारंभिकाक्षर द्वारा संग्रह में लेखक खोजता है।

**पैरामीटर** | **प्रकार** | **विवरण** |
| --- | --- | --- |
| name | java.lang.String | खोजने के लिए लेखक का नाम। |
| initials | java.lang.String | खोजने के लिए लेखक के प्रारंभिकाक्षर। |

**वापसी:**  
com.aspose.slides.ICommentAuthor[] - लेखक या null.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह में निर्दिष्ट सूचकांक पर लेखक हटाता है।

**पैरामीटर** | **प्रकार** | **विवरण** |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित सूचकांक। |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

संग्रह में निर्दिष्ट लेखक की पहली उपस्थिति हटाता है।

**पैरामीटर** | **प्रकार** | **विवरण** |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | संग्रह से हटाने के लिए लेखक। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी लेखकों को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

संग्रह के माध्यम से इटरैट करने वाला एक enumerator लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरैट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

पूरे संग्रह के लिए एक java iterator लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - एक java.util.Iterator जो पूरे संग्रह के लिए है।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर** | **प्रकार** | **विवरण** |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संग्रह तक पहुंच समकालिक (थ्रेड-सेफ़) है या नहीं, यह दर्शाने वाला मान लौटाता है। केवल-पढ़ने-योग्य boolean.

**वापसी:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक synchronization root लौटाता है। केवल-पढ़ने-योग्य Object.

**वापसी:**  
java.lang.Object