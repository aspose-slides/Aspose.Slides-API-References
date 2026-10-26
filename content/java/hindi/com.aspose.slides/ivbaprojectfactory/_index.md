---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: COM इंटरफ़ेस के माध्यम से VBA प्रोजेक्ट बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

COM इंटरफ़ेस के माध्यम से VBA प्रोजेक्ट बनाने की अनुमति देता है
## Methods

| Method | Description |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | नया VBA प्रोजेक्ट बनाता है। |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLE कंटेनर से VBA प्रोजेक्ट पढ़ता है। |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

नया VBA प्रोजेक्ट बनाता है।

**रिटर्न:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - नया VBA प्रोजेक्ट

### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

OLE कंटेनर से VBA प्रोजेक्ट पढ़ता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Ole डेटा byte[] |

**रिटर्न:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - पढ़ा गया VBA प्रोजेक्ट