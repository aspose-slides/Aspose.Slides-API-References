---
title: group method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathsubscriptelement/group/
weight: 80
---
## group(self) {#}
این عنصر را با استفاده از یک پرانتز منحنی پایین در یک گروه قرار می‌دهد

### Returns
نمونه جدیدی از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند پرانتز منحنی پایین یا کاراکتر دیگری در یک گروه قرار می‌دهد

### Returns
نمونه جدیدی از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| character | **char** | کاراکتر گروه‌بندی مانند پرانتز منحنی پایین (U+23DF) یا هر کاراکتر دیگری |
| position | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | موقعیت کاراکتر گروه‌بندی |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | تراز عمودی کاراکتر گروه.<br/><br/>            تطبیق شی را نسبت به خط پایه مشخص می‌کند.<br/><br/>            به عنوان مثال، هنگامی که کاراکتر گروه بالای شی قرار دارد، <br/><br/>            VerticalJustification of Top نشان می‌دهد که بالای شی روی خط پایه قرار می‌گیرد؛<br/><br/>            هنگامی که VerticalJustification به Bottom تنظیم شده باشد، پایین شی روی خط پایه قرار دارد |

### See Also
* کلاس [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)
* کلاس [`MathSubscriptElement`](/slides/python-net/fa/aspose.slides.mathtext/mathsubscriptelement)
* enumeration [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)