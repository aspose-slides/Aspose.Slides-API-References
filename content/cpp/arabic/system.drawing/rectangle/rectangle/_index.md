---
title: Rectangle()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نسخة جديدة من كائن Rectangle الذي يمثل مستطيلاً بإحداثيات X و Y وقيم العرض والارتفاع مضبوطة على 0.
type: docs
weight: 1
url: /ar/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() constructor

يقوم بإنشاء نسخة جديدة من الكائن [Rectangle](../) الذي يمثل مستطيلاً بإحداثيات X و Y وقيم العرض والارتفاع مضبوطة على 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) constructor

يقوم بإنشاء نسخة جديدة من الكائن [Rectangle](../) الذي يمثل مستطيلاً مع الإحداثيات المحددة للزاوية اليسرى العليا وعرضه وارتفاعه.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | int | قيمة إحداثي X للزاوية اليسرى العليا للمستطيل |
| y | int | قيمة إحداثي Y للزاوية اليسرى العليا للمستطيل |
| width | int | عرض المستطيل |
| height | int | ارتفاع المستطيل |

## Rectangle::Rectangle(const Point\&, const Size\&) constructor

يقوم بإنشاء نسخة جديدة من الكائن [Rectangle](../) الذي يمثل مستطيلاً حيث تُحدّد إحداثيات زاويته اليسرى العليا ككائن من الفئة [Point](../../point/)، وعرضه وارتفاعه ككائن من الفئة [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| location | const [Point](../../point/)\& | يحدّد موقع الزاوية اليسرى العليا للمستطيل |
| size | const [Size](../../size/)\& | يحدّد عرض وارتفاع المستطيل |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) constructor

يقوم بإنشاء نسخة جديدة من الكائن [Rectangle](../) الذي يمثل المستطيل المكافئ للمعطى.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | نسخة من الفئة **System::Windows::Forms::Screen::Rectangle_** التي تحدّد موضع وحجم المستطيل الذي سيُمثّله الكائن المُنشأ |

## انظر أيضًا

* الفئة [Rectangle](../)
* الفئة [Point](../../point/)
* الفئة [Size](../../size/)
* النطاق [System::Drawing](../../)
* المكتبة [Aspose.Slides](../../../)