---
title: IChartSeriesGroup class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup فئة

يمثل مجموعة من السلاسل.

يعرض نوع IChartSeriesGroup الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`type`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/type/) | إرجاع نوع هذه المجموعة من السلاسل.<br/>            للقراءة فقط [`CombinableSeriesTypesGroup`](/slides/python-net/ar/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | يشير إلى ما إذا كانت سلاسل هذه المجموعة مُرسَّمة على المحور الثانوي.<br/>            للقراءة فقط **bool**. |
| [`series`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/series/) | إرجاع مجموعة قراءة فقط من سلاسل المخطط.<br/>            للقراءة فقط [`IChartSeriesReadonlyCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | يوفر الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي.<br/>            للقراءة فقط [`IUpDownBarsManager`](/slides/python-net/ar/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/gap_width/) | يسترجع أو يعيّن المسافة بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط.<br/>            يجب أن تكون القيمة بين 0 و 500.<br/>            للقراءة والكتابة **int**. |
| [`gap_depth`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/gap_depth/) | يسترجع أو يعيّن المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد كنسبة مئوية من عرض العلامة.<br/>            يجب أن تكون القيمة بين 0 و 500.<br/>            للقراءة والكتابة **int**. |
| [`first_slice_angle`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | يسترجع أو يعيّن زاوية الشريحة الأولى من مخطط الفطيرة أو الدونات، <br/>            بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة).<br/>            للقراءة والكتابة **int**. |
| [`is_color_varied`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف.<br/>            للقراءة والكتابة **bool**. |
| [`has_series_lines`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الأعمدة المكدسة ومخططات OfPie.<br/>            للقراءة والكتابة **bool**. |
| [`overlap`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/overlap/) | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%).<br/>             - -100%: أقصى مسافة (الأشرطة منفصلة تمامًا).<br/>             - 0%: توضع الأشرطة جنبًا إلى جنب دون تداخل أو مسافة.<br/>             - 100%: أقصى تداخل (الأشرطة تتداخل تمامًا مع بعضها).<br/>             هذه الخاصية للقراءة والكتابة **int**. |
| [`second_pie_size`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو مخطط شريط-من-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 في المئة).<br/>            للقراءة والكتابة **int**. |
| [`pie_split_position`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | يحدد قيمة تُستخدم لتحديد أي نقاط بيانات توجد في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة.<br/>            تُستخدم مع خاصية PieSplitBy.<br/>            للقراءة والكتابة **float**. |
| [`pie_split_by`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | يحدد كيفية تحديد أي نقاط بيانات توجد في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو شريط-من-فطيرة.<br/>            للقراءة والكتابة [`PieSplitType`](/slides/python-net/ar/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | معلومات الانقسام المخصص لمخطط فطيرة-من-فطيرة أو شريط-من-فطيرة مع انقسام مخصص.<br/>            يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط فطيرة-من-فطيرة أو <br/>            شريط-من-فطيرة.<br/>            للقراءة فقط [`IPieSplitCustomPointCollection`](/slides/python-net/ar/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90 في المئة من حجم منطقة الرسم).<br/>            للقراءة والكتابة **int**. |
| [`bubble_size_scale`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 في المئة من الحجم الافتراضي).<br/>            للقراءة والكتابة **int**. |
| [`hi_low_lines_format`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | يحدد تنسيق HiLowLines.<br/>            تُطبق HiLowLines مع أنواع المخططات HiLowClose و OpenHiLowClose و VolumeHiLowClose و VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقعات.<br/>            للقراءة والكتابة [`BubbleSizeRepresentationType`](/slides/python-net/ar/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

يحصل على العنصر في الفهرس المحدد.

## الفهرس

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection وenum CombinableSeriesTypesGroup.  
2) مجموعة السلاسل تحتوي على بعض خصائص السلاسل التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلاسل").  
"خصائص مجموعة السلاسل" في فئة ChartSeriesGroup هي للقراءة والكتابة.  
يمكن لكل من "خصائص مجموعة السلاسل" أن يكون له إسقاط للقراءة فقط في فئة ChartSeries.

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)