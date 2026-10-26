---
title: group method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathblock/group/
weight: 130
---
## group(self) {#}
این عنصر را با استفاده از یک براکت کروی پایین در یک گروه قرار می‌دهد

### Returns
نمونه جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند براکت کروی پایین یا دیگری در یک گروه قرار می‌دهد

### Returns
نمونه جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| character | **char** | کاراکتر گروه‌بندی مانند BOTTOM CURLY BRACKET (U+23DF) یا هر کاراکتر دیگری |
| position | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | موقعیت کاراکتر گروه‌بندی |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | تعیین عمودی کاراکتر گروه.<br/><br/>            تنظیمات تراز شی نسبت به خط مبنا را مشخص می‌کند.<br/><br/>            به عنوان مثال، وقتی کاراکتر گروه بالای شی قرار دارد، <br/><br/>            VerticalJustification of Top نشان می‌دهد که بالای شی بر روی خط مبنا قرار دارد؛<br/><br/>            وقتی VerticalJustification برابر Bottom باشد، پایین شی بر روی خط مبنا قرار می‌گیرد |

### See Also
* کلاس [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)
* کلاس [`MathBlock`](/slides/python-net/fa/aspose.slides.mathtext/mathblock)
* شمارش [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)