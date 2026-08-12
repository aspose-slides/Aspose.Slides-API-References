---
title: GraphicsPath()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़िल मोड के साथ GraphicsPath क्लास की नई इंस्टेंस बनाता है।
type: docs
weight: 1
url: /hi/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) कंस्ट्रक्टर

निर्दिष्ट फ़िल मोड के साथ [GraphicsPath](../) क्लास की नई इंस्टेंस बनाता है।

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | बनायी जा रही वस्तु द्वारा दर्शाए गये बंद पाथ के अंदरूनी हिस्से को किस प्रकार भरना है, यह निर्दिष्ट करता है |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) कंस्ट्रक्टर

निर्दिष्ट पाथ का प्रतिनिधित्व करने वाली [GraphicsPath](../) ऑब्जेक्ट की नई इंस्टेंस बनाता है।

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | एक एरे जिसमें वे बिंदु होते हैं जो बनायी जा रही वस्तु द्वारा दर्शाए गये पाथ को परिभाषित करते हैं |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एक एरे जिसमें उन बिंदुओं के प्रकार के मान होते हैं जो **pts** एरे में होते हैं |
| fillMode | [FillMode](../../fillmode/) | बनायी जा रही वस्तु द्वारा दर्शाए गये बंद पाथ के अंदरूनी हिस्से को किस प्रकार भरना है, यह निर्दिष्ट करता है |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) कंस्ट्रक्टर

निर्दिष्ट पाथ का प्रतिनिधित्व करने वाली [GraphicsPath](../) ऑब्जेक्ट की नई इंस्टेंस बनाता है।

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | एक एरे जिसमें वे बिंदु होते हैं जो बनायी जा रही वस्तु द्वारा दर्शाए गये पाथ को परिभाषित करते हैं |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एक एरे जिसमें उन बिंदुओं के प्रकार के मान होते हैं जो **pts** एरे में होते हैं |
| fillMode | [FillMode](../../fillmode/) | बनायी जा रही वस्तु द्वारा दर्शाए गये बंद पाथ के अंदरूनी हिस्से को किस प्रकार भरना है, यह निर्दिष्ट करता है |

## GraphicsPath::GraphicsPath(const SkPath\&) कंस्ट्रक्टर

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## देखें

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [GraphicsPath](../)
* क्लास [Point](../../../system.drawing/point/)
* क्लास [PointF](../../../system.drawing/pointf/)
* नेमस्पेस [System::Drawing::Drawing2D](../../)
* लाइब्रेरी [Aspose.Slides](../../../)