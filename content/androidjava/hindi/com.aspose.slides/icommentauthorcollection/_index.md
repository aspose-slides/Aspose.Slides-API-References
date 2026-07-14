---
title: ICommentAuthorCollection
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: टिप्पणी लेखकों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icommentauthorcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

टिप्पणी लेखकों के संग्रह का प्रतिनिधित्व करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | संग्रह के अंत में नया लेखक जोड़ता है। |
| [toArray()](#toArray--) | सभी लेखकों के साथ एक ऐरे बनाता और लौटाता है। |
| [findByName(String name)](#findByName-java.lang.String-) | नाम से संग्रह में लेखक को खोजता है। |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | नाम और प्रारम्भिक अक्षरों से संग्रह में लेखक को खोजता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर संग्रह से लेखक को हटाता है। |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | संग्रह में निर्दिष्ट लेखक की पहली उपस्थिति को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी लेखकों को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी मान:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

संग्रह के अंत में नया लेखक जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | नए लेखक का नाम। |
| initials | java.lang.String | नए लेखक के प्रारम्भिक अक्षर। |

**वापसी मान:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - नया [ICommentAuthor](../../com.aspose.slides/icommentauthor) ऑब्जेक्ट।
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

सभी लेखकों के साथ एक ऐरे बनाता और लौटाता है।

**वापसी मान:**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) का ऐरे
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

नाम से संग्रह में लेखक को खोजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | खोजने के लिए लेखक का नाम। |

**वापसी मान:**
com.aspose.slides.ICommentAuthor[] - लेखक या null।
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

नाम और प्रारम्भिक अक्षरों से संग्रह में लेखक को खोजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | खोजने के लिए लेखक का नाम। |
| initials | java.lang.String | खोजने के लिए लेखक के प्रारम्भिक अक्षर। |

**वापसी मान:**
com.aspose.slides.ICommentAuthor[] - लेखक या null।
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर संग्रह से लेखक को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए तत्व का शून्य-आधारित इंडेक्स। |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

संग्रह में निर्दिष्ट लेखक की पहली उपस्थिति को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | संग्रह से हटाने के लिए लेखक। |
### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी लेखकों को हटाता है।