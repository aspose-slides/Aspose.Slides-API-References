---
title: group method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathbar/group/
weight: 80
---
## group(self) {#}
این عنصر را با استفاده از bottom curly bracket در یک گروه قرار می‌دهد

### باز می‌گرداند
نمونهٔ جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند bottom curly bracket یا کاراکتر دیگری در یک گروه قرار می‌دهد

### باز می‌گرداند
نمونهٔ جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| character | **char** | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | Position of grouping character |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | Vertical justification of group character.<br/><br/>            تراز شیء نسبت به خط پایه را تعیین می‌کند.<br/><br/>            به عنوان مثال، هنگامی که کاراکتر گروه بالای شیء قرار دارد، <br/><br/>            تنظیم VerticalJustification به Top به این معنی است که بالای شیء بر روی خط پایه است؛<br/><br/>            زمانی که VerticalJustification بر روی Bottom تنظیم شود، پایین شیء بر روی خط پایه قرار می‌گیرد |

### موارد مرتبط
* کلاس [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)
* کلاس [`MathBar`](/slides/python-net/fa/aspose.slides.mathtext/mathbar)
* شمارش [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)