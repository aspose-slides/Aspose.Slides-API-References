---
title: IVbaModuleCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: VBA प्रोजेक्ट मॉड्यूल का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ivbamodulecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

VBA प्रोजेक्ट मॉड्यूल का संग्रह दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA प्रोजेक्ट में एक नया खाली मॉड्यूल जोड़ता है। |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | संग्रह से किसी विशिष्ट वस्तु की पहली उपस्थिति को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न्स:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

VBA प्रोजेक्ट में एक नया खाली मॉड्यूल जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | मॉड्यूल का नाम |

**रिटर्न्स:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - जोड़ा गया मॉड्यूल।

### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

संग्रह से किसी विशिष्ट वस्तु की पहली उपस्थिति को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | संग्रह से हटाने के लिए मॉड्यूल। |