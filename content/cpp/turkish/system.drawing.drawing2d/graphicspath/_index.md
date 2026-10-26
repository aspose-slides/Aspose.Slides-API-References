---
title: GraphicsPath
second_title: Aspose.Slides for C++ API Referansı
description: "Bağlantılı çizgiler ve eğrilerden oluşan bir küme temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığında veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 66
url: /tr/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath sınıfı

Bağlantılı çizgiler ve eğrilerden oluşan bir küme temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığında veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi argüman olarak fonksiyonlara geçirin.

```cpp
class GraphicsPath : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen eliptik yay ekler. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen eliptik yay ekler. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen eliptik yay ekler. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen eliptik yay ekler. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Geçerli nesne tarafından temsil edilen yola belirtilen kübik Bezier eğrisi ekler. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Geçerli nesne tarafından temsil edilen yola belirtilen kübik Bezier eğrisi ekler. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Geçerli nesne tarafından temsil edilen yola belirtilen kübik Bezier eğrisi ekler. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen kübik Bezier eğrisi ekler. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Geçerli şekle bağlı bir dizi kübik Bezier eğrisi ekler. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Geçerli şekle bağlı bir dizi kübik Bezier eğrisi ekler. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen kapalı eğri ekler. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen kapalı eğri ekler. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen eğri ekler. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen eğri ekler. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen eğri ekler. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen eğri ekler. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen elips ekler. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Geçerli nesne tarafından temsil edilen yola belirtilen elips ekler. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Geçerli nesne tarafından temsil edilen yola belirtilen elips ekler. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Geçerli nesne tarafından temsil edilen yola belirtilen elips ekler. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Geçerli nesne tarafından temsil edilen yola belirtilen çizgi ekler. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Geçerli nesne tarafından temsil edilen yola belirtilen çizgi ekler. |
| void [AddLine](./addline/)(int, int, int, int) | Geçerli nesne tarafından temsil edilen yola belirtilen çizgi ekler. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen çizgi ekler. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Geçerli nesne tarafından temsil edilen yola bağlı bir dizi çizgi segmenti ekler. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Geçerli nesne tarafından temsil edilen yola bağlı bir dizi çizgi segmenti ekler. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Geçerli nesne tarafından temsil edilen yola belirtilen yolu ekler. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen pasta şeklinin ana hatlarını ekler. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen pasta şeklinin ana hatlarını ekler. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Geçerli nesne tarafından temsil edilen yola belirtilen pasta şeklinin ana hatlarını ekler. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Geçerli nesne tarafından temsil edilen yola belirtilen çokgen ekler. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Geçerli nesne tarafından temsil edilen yola belirtilen çokgen ekler. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Geçerli nesne tarafından temsil edilen yola belirtilen dikdörtgen ekler. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Geçerli nesne tarafından temsil edilen yola belirtilen dikdörtgen ekler. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Geçerli nesne tarafından temsil edilen yola belirtilen bir dizi dikdörtgen ekler. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Geçerli nesne tarafından temsil edilen yola belirtilen bir dizi dikdörtgen ekler. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Geçerli nesne tarafından temsil edilen yola bir metin dizesi ekler. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Geçerli nesne tarafından temsil edilen yola bir metin dizesi ekler. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Geçerli nesne tarafından temsil edilen yola bir metin dizesi ekler. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Geçerli nesne tarafından temsil edilen yola bir metin dizesi ekler. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Geçerli nesnenin bir kopyasını oluşturur. |
| void [CloseAllFigures](./closeallfigures/)() | Tüm açık şekilleri kapatır ve yenisini başlatır. |
| void [CloseFigure](./closefigure/)() | Geçerli şekli kapatır ve yenisini başlatır. |
| void [Dispose](./dispose/)() | Geçerli nesne tarafından edinilen tüm işletim sistemi kaynaklarını serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için. |
| void [Flatten](./flatten/)() | Yoldaki her eğriyi bağlı bir satır serisine dönüştürerek düzleştirir. 0.25 düzlik değeri kullanılır. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Yoldaki her eğriyi bağlı bir satır serisine dönüştürerek düzleştirir. 0.25 düzlik değeri kullanılır. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Yoldaki her eğriyi bağlı bir satır serisine dönüştürerek düzleştirir. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Geçerli nesnenin doldurma kipini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Geçerli nesne tarafından temsil edilen bir yolu oluşturan noktaları ve türlerini içeren bir [PathData](../pathdata/) nesnesi döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Geçerli nesne tarafından temsil edilen bir yolu oluşturan noktaları içeren bir dizi döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Geçerli nesne tarafından temsil edilen bir yolu oluşturan noktaların türlerini gösteren değerleri içeren bir dizi döndürür. |
| int [get_PointCount](./get_pointcount/)() const | Geçerli nesne tarafından temsil edilen yoldaki nokta sayısını döndürür. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Belirtilen matris ile dönüştürüldüğünde geçerli nesne tarafından temsil edilen yolu sınırlayan bir dikdörtgeni temsil eden bir [RectangleF](../../system.drawing/rectanglef/) nesnesi döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Geçerli nesne tarafından temsil edilen yolda hangi şekil türlerinin bulunduğunu gösteren, Detail::FigureType değerlerinin bit düzeyinde birleşiminden oluşan bir değer döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin bir benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Yoldaki son noktayı temsil eden bir [PointF](../../system.drawing/pointf/) nesnesi döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının bir benzeri. |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Belirtilen doldurma kipine sahip yeni bir [GraphicsPath](./) sınıfı örneği oluşturur. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Belirtilen yolu temsil eden yeni bir [GraphicsPath](./) nesnesi oluşturur. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Belirtilen yolu temsil eden yeni bir [GraphicsPath](./) nesnesi oluşturur. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün bir benzeri. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Belirtilen noktanın, belirtilen [Pen](../../system.drawing/pen/) ile çizildiğinde bu [GraphicsPath](./)'nin (alt) ana hattının içinde olup olmadığını gösterir. UYGULANMADI. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Belirtilen noktanın geçerli nesne tarafından temsil edilen yolda içinde olup olmadığını belirler. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Belirtilen noktanın geçerli nesne tarafından temsil edilen yolda içinde olup olmadığını belirler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin bir benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekten hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekten hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referansla, değer tipindeki nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [Reset](./reset/)() | Tüm noktaları kaldırarak yolu boşaltır. |
| void [Reverse](./reverse/)() | Bu [GraphicsPath](./)'nin PathPoints dizisindeki nokta sırasını tersine çevirir. |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Geçerli nesnenin doldurma kipini ayarlar. |
| void [SetMarkers](./setmarkers/)() | UYGULANMADI. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| void [StartFigure](./startfigure/)() | Yeni bir şekil başlatır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin bir benzeri. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Belirtilen dönüşüm matrisini uygulayarak geçerli nesne tarafından temsil edilen yolu dönüştürür. |
| void [Transform](./transform/)(const SkMatrix\&) |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Bu yolu, orijinal yolun çevresindeki bir anahatla değiştirir. |
|  [~GraphicsPath](./~graphicspath/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [Object](../../system/object/)
* Ad Alanı [System::Drawing::Drawing2D](../)
* Kütüphane [Aspose.Slides](../../)