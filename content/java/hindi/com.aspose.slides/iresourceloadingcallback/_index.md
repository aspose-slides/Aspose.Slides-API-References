---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
url: /hi/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

बाहरी संसाधनों के लोडिंग को प्रबंधित करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | बाहरी संसाधनों की लोडिंग को नियंत्रित करने वाला कॉलबैक मेथड। |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

बाहरी संसाधनों की लोडिंग को नियंत्रित करने वाला कॉलबैक मेथड।

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | लोड हो रहे संसाधन डेटा [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs)। |

**वापसी:**
int - संसाधन लोडिंग निर्णय [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction)।