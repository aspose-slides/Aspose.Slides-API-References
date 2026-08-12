---
title: SaveAdd()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: पिछले Save() मेथड कॉल में निर्दिष्ट फ़ाइल या स्ट्रीम में एक फ्रेम जोड़ता है।
type: docs
weight: 14
url: /hi/system.drawing/image/saveadd/
---
## Image::SaveAdd(const Imaging::EncoderParametersPtr\&) विधि

फ़ाइल या स्ट्रीम में एक फ़्रेम जोड़ता है जो पिछले कॉल में [Save()](../save/) विधि द्वारा निर्दिष्ट किया गया है।

```cpp
void System::Drawing::Image::SaveAdd(const Imaging::EncoderParametersPtr &encoder_params)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | उपयोग हेतु एनकोडर पैरामीटर |

## Image::SaveAdd(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) विधि

फ़ाइल या स्ट्रीम में एक फ़्रेम जोड़ता है जो पिछले कॉल में [Save()](../save/) विधि द्वारा निर्दिष्ट किया गया है।

```cpp
void System::Drawing::Image::SaveAdd(const SharedPtr<Image> &image, const Imaging::EncoderParametersPtr &encoder_params)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../)\>\& | एक [Image](../) वस्तु जिसमें जोड़ने के लिए फ़्रेम होता है |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | उपयोग हेतु एनकोडर पैरामीटर |

## संबंधित देखें

* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Image](../)
* नामस्थान [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)