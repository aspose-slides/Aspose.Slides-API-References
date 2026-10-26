---
title: group method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathbox/group/
weight: 80
---
## group(self) {#}
این عنصر را با استفاده از یک پرانتز کروی زیرین در یک گروه قرار می‌دهد

### بازگشت
یک نمونه جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
این عنصر را با استفاده از کاراکتر گروه‌بندی مانند پرانتز کروی زیرین یا کاراکتر دیگری در یک گروه قرار می‌دهد

### بازگشت
یک نمونه جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | کاراکتر گروه‌بندی مانند BOTTOM CURLY BRACKET (U+23DF) یا هر کاراکتر دیگری |
| position | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | موقعیت کاراکتر گروه‌بندی |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | جهت‌گیری عمودی کاراکتر گروه.<br/><br/>            ترازشی شیء نسبت به خط پایه را تعیین می‌کند.<br/><br/>            به عنوان مثال، وقتی کاراکتر گروه بالای شیء قرار دارد، <br/><br/>            VerticalJustification مقدار Top نشان می‌دهد که بالای شیء روی خط پایه قرار می‌گیرد؛<br/><br/>            وقتی VerticalJustification برابر Bottom باشد، پایین شیء روی خط پایه است |

### موارد مرتبط
* کلاس [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)
* کلاس [`MathBox`](/slides/python-net/fa/aspose.slides.mathtext/mathbox)
* شمارش [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)