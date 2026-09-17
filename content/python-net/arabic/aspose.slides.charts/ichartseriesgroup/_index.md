---
title: IChartSeriesGroup class
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup فئة

يمثل مجموعة من السلاسل.

يُظهر نوع IChartSeriesGroup الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`type`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/type/) | يرجع نوعًا لهذه المجموعة من السلاسل.<br/>            للقراءة فقط [`CombinableSeriesTypesGroup`](/slides/python-net/ar/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | يُشير إلى ما إذا كانت سلاسل هذه المجموعة مُرسومة على محور ثانوي.<br/>            للقراءة فقط **bool**. |
| [`series`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/series/) | يرجع مجموعة للقراءة فقط من سلاسل المخطط.<br/>            للقراءة فقط [`IChartSeriesReadonlyCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | يوفر وصولًا إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي.<br/>            للقراءة فقط [`IUpDownBarsManager`](/slides/python-net/ar/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/gap_width/) | يحدد المسافة بين مجموعات الأعمدة أو الشرائط كنسبة مئوية من عرض العمود أو الشريط.<br/>            قابل للقراءة والكتابة **int**. |
| [`gap_depth`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/gap_depth/) | يرجع أو يحدد المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد.<br/>            قابل للقراءة والكتابة **int**. |
| [`first_slice_angle`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | يحصل أو يحدد زاوية القطعة الأولى في مخطط الفطيرة أو الكعكة،<br/>            بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة).<br/>            قابل للقراءة والكتابة **int**. |
| [`is_color_varied`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف.<br/>            قابل للقراءة والكتابة **bool**. |
| [`has_series_lines`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | صحيح إذا كان المخطط يحتوي على خطوط السلاسل. يُطبق على مخططات الشريط المتراكم و OfPie.<br/>            قابل للقراءة والكتابة **bool**. |
| [`overlap`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/overlap/) | يحدد مقدار تداخل الأعمدة والشرائط في المخططات الثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%).<br/>             - -100%: أقصى مسافة (الأعمدة مفصولة تمامًا).<br/>             - 0%: توضع الأعمدة جنبًا إلى جنب دون تداخل أو مسافة.<br/>             - 100%: أقصى تداخل (الأعمدة تتداخل تمامًا مع بعضها).<br/>             هذه الخاصية قابلة للقراءة والكتابة **int**. |
| [`second_pie_size`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو <br/>            مخطط شريط-في-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و200 بالمئة).<br/>            قابل للقراءة والكتابة **int**. |
| [`pie_split_position`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | يحدد قيمة تُستخدم لتحديد نقاط البيانات الموجودة في الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو شريط-في-فطيرة.<br/>            يُستخدم مع الخاصية PieSplitBy.<br/>            قابل للقراءة والكتابة **float**. |
| [`pie_split_by`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | يحدد طريقة تحديد نقاط البيانات الموجودة في الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو شريط-في-فطيرة.<br/>            قابل للقراءة والكتابة [`PieSplitType`](/slides/python-net/ar/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | معلومات الانقسام المخصص لمخطط فطيرة-في-فطيرة أو شريط-في-فطيرة مع انقسام مخصص.<br/>            يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو <br/>            شريط-في-فطيرة.<br/>            للقراءة فقط [`IPieSplitCustomPointCollection`](/slides/python-net/ar/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | يحدد حجم الفتحة في مخطط الكعكة (يمكن أن يكون بين 10 و90 بالمئة من حجم مساحة الرسم).<br/>            قابل للقراءة والكتابة **int**. |
| [`bubble_size_scale`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | يحدد معامل التحجيم لمخطط الفقاعات (يمكن أن يكون بين 0 و300 بالمئة من الحجم الافتراضي).<br/>            قابل للقراءة والكتابة **int**. |
| [`hi_low_lines_format`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | يحدد تنسيق HiLowLines. <br/>            يُطبق HiLowLines مع أنواع المخططات HiLowClose و OpenHiLowClose و VolumeHiLowClose و VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | يحدد كيف يتم تمثيل قيم حجم الفقاعات في مخطط الفقاعات.<br/>            قابل للقراءة والكتابة [`BubbleSizeRepresentationType`](/slides/python-net/ar/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

يحصل على العنصر في الفهرس المحدد.

## Indexer

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup.  
            2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة").  
            "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup هي قابل للقراءة والكتابة.  
            كل من "خصائص مجموعة السلسلة" يمكن أن يكون لها إسقاط للقراءة فقط في فئة ChartSeries.  


### انظر أيضًا
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)