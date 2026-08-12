---
title: BeginContainer()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान स्थिति के साथ इस ऑब्जेक्ट का कंटेनर सहेजता है, एक नया कंटेनर खोलता और उपयोग करता है और सहेजे गए कंटेनर को लौटाता है।
type: docs
weight: 976
url: /hi/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() विधि

Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) विधि

Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | नया कंटेनर का स्केल ट्रांसफ़ॉर्मेशन निर्दिष्ट करने वाला आयत। **srcrect** के साथ मिलकर उपयोग किया जाता है |
| srcrect | [Rectangle](../../rectangle/) | नया कंटेनर का स्केल ट्रांसफ़ॉर्मेशन निर्दिष्ट करने वाला आयत। **dstrect** के साथ मिलकर उपयोग किया जाता है |
| unit | [GraphicsUnit](../../graphicsunit/) | नया कंटेनर की माप इकाई को निर्दिष्ट करने वाला मान |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) विधि

Saves a container with the current state of this object, opens and uses a new container and returns the saved container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | नया कंटेनर का स्केल ट्रांसफ़ॉर्मेशन निर्दिष्ट करने वाला आयत। **srcrect** के साथ मिलकर उपयोग किया जाता है |
| srcrect | [RectangleF](../../rectanglef/) | नया कंटेनर का स्केल ट्रांसफ़ॉर्मेशन निर्दिष्ट करने वाला आयत। **dstrect** के साथ मिलकर उपयोग किया जाता है |
| unit | [GraphicsUnit](../../graphicsunit/) | नया कंटेनर की माप इकाई को निर्दिष्ट करने वाला मान |

## संबंधित देखें

* एन्युम [GraphicsUnit](../../graphicsunit/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* क्लास [Graphics](../)
* क्लास [Rectangle](../../rectangle/)
* क्लास [RectangleF](../../rectanglef/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)