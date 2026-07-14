---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create VBA project via COM interface
type: docs
url: /hi/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

COM interface के माध्यम से VBA project बनाने की अनुमति देता है
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | नया VBA project बनाता है। |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLE कंटेनर से VBA project पढ़ता है। |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


नया VBA project बनाता है।

**रिटर्न:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - नई VBA project
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


OLE कंटेनर से VBA project पढ़ता है।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | Ole डेटा byte[] |

**रिटर्न:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - पढ़ा VBA project