---
title: Trendline class
second_title: مرجع API Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/trendline/
---
## Trendline فئة

الفئة تمثل خط الاتجاه لسلسلة المخطط

يعرض نوع Trendline الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`trendline_name`](/slides/python-net/ar/aspose.slides.charts/trendline/trendline_name/) | يحصل أو يحدد اسم خط الاتجاه.<br/>            قراءة/كتابة **str**. |
| [`trendline_type`](/slides/python-net/ar/aspose.slides.charts/trendline/trendline_type/) | يحصل أو يحدد نوع خط الاتجاه.<br/>            قراءة/كتابة [`TrendlineType`](/slides/python-net/ar/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/ar/aspose.slides.charts/trendline/format/) | يمثل تنسيق خط الاتجاه.<br/>            قراءة/كتابة [`IFormat`](/slides/python-net/ar/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/ar/aspose.slides.charts/trendline/backward/) | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه قبل بيانات السلسلة التي يتم تحليلها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة غير سالبة.<br/>            قراءة/كتابة **float**. |
| [`forward`](/slides/python-net/ar/aspose.slides.charts/trendline/forward/) | يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه بعد بيانات السلسلة التي يتم تحليلها. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة غير سالبة.<br/>            قراءة/كتابة **float**. |
| [`intercept`](/slides/python-net/ar/aspose.slides.charts/trendline/intercept/) | يحدد القيمة التي يتقاطع عندها خط الاتجاه مع المحور ص. يجب أن تكون هذه الخاصية مدعومة فقط عندما يكون نوع خط الاتجاه exp أو linear أو poly.<br/>            قراءة/كتابة **float**. |
| [`display_equation`](/slides/python-net/ar/aspose.slides.charts/trendline/display_equation/) | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية كما قيمة Rsquaredvalue).<br/>            قراءة/كتابة **bool**. |
| [`order`](/slides/python-net/ar/aspose.slides.charts/trendline/order/) | يحدد رتبة خط الاتجاه كثير الحدود. يتم تجاهله لأنواع خطوط الاتجاه الأخرى. يجب أن تكون القيمة بين 2 و 6.<br/>            قراءة/كتابة **int**. |
| [`period`](/slides/python-net/ar/aspose.slides.charts/trendline/period/) | يحدد فترة خط الاتجاه لخط المتوسط المتحرك. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 255.<br/>            قراءة/كتابة **int**. |
| [`display_r_squared_value`](/slides/python-net/ar/aspose.slides.charts/trendline/display_r_squared_value/) | يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية كما المعادلة).<br/>            قراءة/كتابة **bool**. |
| [`related_legend_entry`](/slides/python-net/ar/aspose.slides.charts/trendline/related_legend_entry/) | يمثل مدخل وسيلة الإيضاح المرتبط بهذا خط الاتجاه<br/>            قراءة فقط [`ILegendEntryProperties`](/slides/python-net/ar/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/ar/aspose.slides.charts/trendline/text_frame_for_overriding/) | يمكن أن يحتوي على نص منسق غني. إذا لم تكن هذه الخاصية None فإن قيمة النص المنسق هذه تتجاوز النص المُولد تلقائيًا لملصق البيانات.<br/> النص المُولد تلقائيًا لملصق البيانات يعني النص الذي يتم إدارته بواسطة الخصائص ShowSeriesName، ShowValue، ... ويتم تنسيقه باستخدام الخاصية TextFormatManager.TextFormat.<br/> قراءة فقط [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ar/aspose.slides.charts/trendline/text_format/) | يرجع تنسيق النص.<br/>            قراءة فقط [`IChartTextFormat`](/slides/python-net/ar/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/trendline/chart/) | يرجع المخطط الأب.<br/>            قراءة فقط [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/trendline/presentation/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ar/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | تهيئة TextFrameForOverriding بالنص في المعامل "text".<br/> إذا كان TextFrameForOverriding مبدئًا بالفعل فسيتم ببساطة تغيير نصه. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)