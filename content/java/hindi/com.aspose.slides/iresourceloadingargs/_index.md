---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: बाहरी संसाधन लोड करने के तर्कों के लिए इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

बाहरी संसाधन लोड करने के तर्कों के लिए इंटरफ़ेस।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Imported presentation में निर्दिष्ट संसाधन का मूल URI। |
| [getUri()](#getUri--) | वह URI जिसका उपयोग डाउनलोड के लिए किया जाता है यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) लौटाता है। |
| [setUri(String value)](#setUri-java.lang.String-) | वह URI जिसका उपयोग डाउनलोड के लिए किया जाता है यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) लौटाता है। |
| [setData(byte[] data)](#setData-byte---) | सेट किया गया उपयोगकर्ता डेटा वह संसाधन का जिसका उपयोग किया जाता है यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) लौटाता है। |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

Imported presentation में निर्दिष्ट संसाधन का मूल URI।

**रिटर्न:**  
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```

यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) लौटाता है तो डाउनलोड के लिए उपयोग किया जाने वाला संसाधन URI। प्रारंभिक रूप से यह संसाधन के मूल URI पर सेट किया जाता है, लेकिन इसे किसी भी मान में पुनः परिभाषित किया जा सकता है।

**रिटर्न:**  
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) लौटाता है तो डाउनलोड के लिए उपयोग किया जाने वाला संसाधन URI। प्रारंभिक रूप से यह संसाधन के मूल URI पर सेट किया जाता है, लेकिन इसे किसी भी मान में पुनः परिभाषित किया जा सकता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) लौटाता है तो सेट किया गया उपयोगकर्ता डेटा वह संसाधन का।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | संसाधन के प्रदान किए गए डेटा byte[] |