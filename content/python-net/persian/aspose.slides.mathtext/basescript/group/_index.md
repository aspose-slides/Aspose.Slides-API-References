---
title: group method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/basescript/group/
weight: 70
---
## group(self) {#}
این عنصر را با استفاده از یک پرانتز منحنی پایین در یک گروه قرار می‌دهد

### بازگرداندن

نمونه جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
این عنصر را با استفاده از یک حرف گروه‌بندی مانند پرانتز منحنی پایین یا حرف دیگری در یک گروه قرار می‌دهد

### بازگرداندن

نمونه جدید از نوع [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| character | **char** | حرف گروه‌بندی مانند پرانتز منحنی پایین (U+23DF) یا هر حرف دیگری |
| position | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | موقعیت حرف گروه‌بندی |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions) | همترازی عمودی حرف گروه.<br/><br/>            مشخص می‌کند که تراز شیء نسبت به خط پایه چگونه است.<br/><br/>            به عنوان مثال، وقتی حرف گروه بالای شیء قرار دارد، <br/><br/>            VerticalJustification of Top به این معنی است که بالای شیء بر خط پایه قرار می‌گیرد؛<br/><br/>            وقتی VerticalJustification بر روی Bottom تنظیم شود، پایین شیء بر خط پایه قرار می‌گیرد |



### مراجع
* کلاس [`BaseScript`](/slides/python-net/fa/aspose.slides.mathtext/basescript)
* کلاس [`IMathGroupingCharacter`](/slides/python-net/fa/aspose.slides.mathtext/imathgroupingcharacter)
* شمارش [`MathTopBotPositions`](/slides/python-net/fa/aspose.slides.mathtext/mathtopbotpositions)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)