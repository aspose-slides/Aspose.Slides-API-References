---
title: IResourceLoadingCallback
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: बाहरी संसाधनों के लोडिंग को प्रबंधित करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

बाहरी संसाधनों के लोडिंग को प्रबंधित करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।

## विधियां

| विधि | विवरण |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | बाहरी संसाधनों के लोडिंग को नियंत्रित करने वाला कॉलबैक मेथड। |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

बाहरी संसाधनों के लोडिंग को नियंत्रित करने वाला कॉलबैक मेथड।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | लोड हो रहे संसाधन डेटा [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs)। |

**रिटर्न:**
int - संसाधन लोडिंग निर्णय [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction)।