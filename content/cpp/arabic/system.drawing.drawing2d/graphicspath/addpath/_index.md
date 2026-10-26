---
title: AddPath()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضيف المسار المحدد إلى المسار المُمَثَّل بواسطة الكائن الحالي.
type: docs
weight: 222
url: /ar/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) method

يضيف المسار المحدد إلى المسار المُمَثَّل بواسطة الكائن الحالي.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | المسار للإضافة |
| connect | **bool** | True يحدد أن الشكل الأخير الأول في **path** هو جزء من الشكل الأخير للمسار المُمَثَّل بواسطة الكائن الحالي؛ false يحدد أن الشكل الأول في **path** والشكل الأخير في المسار المُمَثَّل بواسطة الكائن الحالي هما شكلان منفصلان |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)