---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /hi/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

चार्ट तत्व की वास्तविक स्थिति को निर्दिष्ट करता है।
## विधियाँ

| विधि | वर्णन |
| --- | --- |
| [getActualX()](#getActualX--) | चार्ट के बाएँ ऊपर कोने के सापेक्ष चार्ट तत्व का वास्तविक x स्थल (बाएँ) निर्दिष्ट करता है। |
| [getActualY()](#getActualY--) | चार्ट के बाएँ ऊपर कोने के सापेक्ष चार्ट तत्व का वास्तविक शीर्ष निर्दिष्ट करता है। |
| [getActualWidth()](#getActualWidth--) | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। |
| [getActualHeight()](#getActualHeight--) | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

चार्ट के बाएँ ऊपर कोने के सापेक्ष चार्ट तत्व का वास्तविक x स्थल (बाएँ) निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। फ़्लोट पढ़ें।

**रिटर्न:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

चार्ट के बाएँ ऊपर कोने के सापेक्ष चार्ट तत्व का वास्तविक शीर्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। फ़्लोट पढ़ें।

**रिटर्न:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। फ़्लोट पढ़ें।

**रिटर्न:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। फ़्लोट पढ़ें।

**रिटर्न:**
float