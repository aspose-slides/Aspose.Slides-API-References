---
title: group method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
این عنصر را با استفاده از یک قوس‌خم پایینی در یک گروه قرار می‌دهد

### بازگشت

نمونه جدیدی از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند قوس‌خم پایینی یا هر کاراکتر دیگری در یک گروه قرار می‌دهد

### بازگشت

نمونه جدیدی از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| character | **char** | کاراکتر گروه‌بندی مانند قوس‌خم پایینی (U+23DF) یا هر کاراکتر دیگری |
| position | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | موقعیت کاراکتر گروه‌بندی |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | Vertical justification of group character.<br/><br/>            Specifies the alignment of the object with respect to the baseline.<br/><br/>            For example, when the group character is above the object, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |



### موارد مرتبط
* کلاس [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)
* کلاس [`MathDelimiter`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter)
* شمارش [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)