---
title: ChartSeriesGroup class
second_title: مرجع API لAspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/chartseriesgroup/
---
## فئة ChartSeriesGroup

يمثل مجموعة من السلاسل.

نوع ChartSeriesGroup يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`type`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/type/) | يعيد نوع مجموعة السلاسل هذه.<br/>            قراءة فقط [`CombinableSeriesTypesGroup`](/slides/python-net/ar/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | يشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على محور ثانوي.<br/>            قراءة فقط **bool**. |
| [`series`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/series/) | يعيد مجموعة من السلاسل.<br/>            قراءة فقط [`IChartSeriesReadonlyCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/up_down_bars/) | يوفر وصولاً إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط العمودي.<br/>            قراءة فقط [`IUpDownBarsManager`](/slides/python-net/ar/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/gap_width/) | يحدد المسافة بين مجموعات الأعمدة أو الشريط، كنسبة مئوية من عرض العمود أو الشريط.<br/>            قراءة/كتابة **int**. |
| [`gap_depth`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/gap_depth/) | يعيد أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد.<br/>            قراءة/كتابة **int**. |
| [`first_slice_angle`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | يحصل أو يضبط زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، <br/>            بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة).<br/>            قراءة/كتابة **int**. |
| [`doughnut_hole_size`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | يحدد حجم الفتحة في مخطط الدونات (يمكن أن تكون بين 0 و 90 بالمئة <br/>            من حجم مساحة الرسم).<br/>            قراءة/كتابة **int**. |
| [`overlap`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/overlap/) | يحدد مقدار التداخل بين الأعمدة والشريط في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%).<br/>             - -100%: أقصى مسافة (الأعمدة منفصلة تمامًا).<br/>             - 0%: توضع الأعمدة جنبًا إلى جنب دون تداخل أو مسافة.<br/>             - 100%: أقصى تداخل (الأعمدة تتداخل تمامًا مع بعضها).<br/>             هذه الخاصية قراءة/كتابة **int**. |
| [`second_pie_size`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/second_pie_size/) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو <br/>            مخطط شريط-من-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن <br/>            أن تكون بين 5 و 200 بالمئة).<br/>            قراءة/كتابة **int**. |
| [`bubble_size_representation`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات.<br/>            قراءة/كتابة [`BubbleSizeRepresentationType`](/slides/python-net/ar/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/pie_split_position/) | يحدد قيمة ستُستخدم لتحديد نقاط البيانات <br/>            التي تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو مخطط شريط-من-فطيرة. <br/>            تُستخدم مع الخاصية PieSplitBy.<br/>            قراءة/كتابة **float**. |
| [`pie_split_by`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/pie_split_by/) | يحدد طريقة تحديد نقاط البيانات التي تكون في الفطيرة أو الشريط الثاني <br/>            في مخطط فطيرة-من-فطيرة أو مخطط شريط-من-فطيرة.<br/>            قراءة/كتابة [`PieSplitType`](/slides/python-net/ar/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/is_color_varied/) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف.<br/>            قراءة/كتابة **bool**. |
| [`has_series_lines`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/has_series_lines/) | صحيح إذا كان للمخطط خطوط السلاسل. يُطبق على مخططات الشريط المتكدس ومخططات OfPie.<br/>            قراءة/كتابة **bool**. |
| [`hi_low_lines_format`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | يحدد تنسيق HiLowLines. <br/>            يُطبق HiLowLines مع أنواع المخططات HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | يحدد معامل التحجيم لمخطط الفقاعات (يمكن أن يكون <br/>            بين 0 و 300 بالمئة من الحجم الافتراضي).<br/>            قراءة/كتابة **int**. |
| [`pie_split_custom_points`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | معلومات الانقسام المخصص لمخطط فطيرة-من-فطيرة أو شريط-من-فطيرة مع انقسام مخصص.<br/>            يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو <br/>            شريط-من-فطيرة.<br/>            قراءة فقط [`PieSplitCustomPointCollection`](/slides/python-net/ar/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/chart/) | يعيد المخطط الأب.<br/>            قراءة فقط [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/presentation/) |  |

يحصل على العنصر عند الفهرس المحدد.

## الفهرس

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection والعدد CombinableSeriesTypesGroup.
2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة").
   "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup هي قراءة/كتابة.
   يمكن لكل من "خصائص مجموعة السلسلة" أن تكون لها إسقاط قراءة فقط في فئة ChartSeries.


### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)