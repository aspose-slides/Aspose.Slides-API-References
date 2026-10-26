---
title: group method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathsuperscriptelement/group/
weight: 80
---
## group(self) {#}
این عنصر را با استفاده از یک کروشهٔ پایین در یک گروه قرار می‌دهد

### بازگشت
نمونهٔ جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند کروشهٔ پایین یا هر کاراکتر دیگری در یک گروه قرار می‌دهد

### بازگشت
نمونهٔ جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| character | **char** | کاراکتر گروه‌بندی مانند BOTTOM CURLY BRACKET (U+23DF) یا هر کاراکتر دیگری |
| position | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | موقعیت کاراکتر گروه‌بندی |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | توزیع عمودی کاراکتر گروه.<br/><br/>            تعیین‌کنندهٔ تراز شیء نسبت به خط پایه است.<br/><br/>            به عنوان مثال، زمانی که کاراکتر گروه بالای شیء باشد، <br/><br/>            VerticalJustification of Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛<br/><br/>            هنگامی که VerticalJustification برابر Bottom تنظیم شود، پایین شیء روی خط پایه قرار می‌گیرد |

### موارد مرتبط
* کلاس [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)
* کلاس [`MathSuperscriptElement`](/slides/python-net/fa/aspose.slides.mathtext/mathsuperscriptelement)
* شمارش [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)