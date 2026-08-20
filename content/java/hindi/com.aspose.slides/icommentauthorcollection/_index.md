---
title: ICommentAuthorCollection
second_title: Aspose.Slides for Java API संदर्भ
description: टिप्पणी लेखकों का एक संग्रह प्रस्तुत करता है।
type: docs
url: /hi/com.aspose.slides/icommentauthorcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

एक टिप्पणी लेखक संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | संग्रह के अंत में नया लेखक जोड़ें। |
| [toArray()](#toArray--) | सभी लेखकों के साथ एक एरे बनाता और लौटाता है। |
| [findByName(String name)](#findByName-java.lang.String-) | नाम द्वारा संग्रह में लेखक खोजें। |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | नाम और आद्याक्षर द्वारा संग्रह में लेखक खोजें। |
| [removeAt(int index)](#removeAt-int-) | संग्रह के निर्दिष्ट इंडेक्स पर लेखक को हटाता है। |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | संग्रह में निर्दिष्ट लेखक की पहली उपस्थिती को हटाता है। |
| [clear()](#clear--) | सभी लेखकों को संग्रह से हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ICommentAuthor](../../com.aspose.slides/icommentauthor)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


संग्रह के अंत में नया लेखक जोड़ें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | नए लेखक का नाम। |
| initials | java.lang.String | नए लेखक के आद्याक्षर। |

**रिटर्न:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - नया [ICommentAuthor](../../com.aspose.slides/icommentauthor) ऑब्जेक्ट।
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


सभी लेखकों के साथ एक एरे बनाता और लौटाता है।

**रिटर्न:**
com.aspose.slides.ICommentAuthor[] - एरे [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


नाम द्वारा संग्रह में लेखक खोजें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | खोजने के लिए लेखक का नाम। |

**रिटर्न:**
com.aspose.slides.ICommentAuthor[] - लेखक या null।
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


नाम और आद्याक्षर द्वारा संग्रह में लेखक खोजें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | खोजने के लिए लेखक का नाम। |
| initials | java.lang.String | खोजने के लिए लेखक के आद्याक्षर। |

**रिटर्न:**
com.aspose.slides.ICommentAuthor[] - लेखक या null।
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


संग्रह के निर्दिष्ट इंडेक्स पर लेखक को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के तत्व का शून्य-आधारित इंडेक्स। |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


संग्रह में निर्दिष्ट लेखक की पहली उपस्थिती को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | एक संग्रह से हटाने के लिए लेखक। |

### clear() {#clear--}
```
public abstract void clear()
```


सभी लेखकों को संग्रह से हटाता है।