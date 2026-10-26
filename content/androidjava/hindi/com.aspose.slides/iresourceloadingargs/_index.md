---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: बाहरी संसाधन लोडिंग तर्कों के लिए इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

बाहरी संसाधन लोडिंग तर्कों के लिए इंटरफ़ेस।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | आयातित प्रस्तुति में निर्दिष्ट संसाधन का मूल URI। |
| [getUri()](#getUri--) | यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) लौटाता है तो डाउनलोड के लिए उपयोग किया जाने वाला संसाधन का URI। |
| [setUri(String value)](#setUri-java.lang.String-) | यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) लौटाता है तो डाउनलोड के लिए उपयोग किया जाने वाला संसाधन का URI। |
| [setData(byte[] data)](#setData-byte---) | यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) लौटाता है तो उपयोगकर्ता द्वारा प्रदान किया गया संसाधन डेटा सेट करता है। |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


आयातित प्रस्तुति में निर्दिष्ट संसाधन का मूल URI।

**रिटर्न:**  
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) लौटाता है तो डाउनलोड के लिए उपयोग किया जाने वाला संसाधन का URI। प्रारंभ में यह संसाधन के मूल URI पर सेट होता है, लेकिन इसे किसी भी मान में पुनर्परिभाषित किया जा सकता है।

**रिटर्न:**  
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) लौटाता है तो डाउनलोड के लिए उपयोग किया जाने वाला संसाधन का URI। प्रारंभ में यह संसाधन के मूल URI पर सेट होता है, लेकिन इसे किसी भी मान में पुनर्परिभाषित किया जा सकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


यदि [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) लौटाता है तो उपयोगकर्ता द्वारा प्रदान किया गया संसाधन डेटा सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | संसाधन का प्रदान किया गया डेटा byte[] |