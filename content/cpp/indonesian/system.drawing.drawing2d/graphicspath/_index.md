---
title: GraphicsPath
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili sekumpulan garis dan kurva yang terhubung. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instansi tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen."
type: docs
weight: 66
url: /id/system.drawing.drawing2d/graphicspath/
---
## Kelas GraphicsPath


Mewakili sekumpulan garis dan kurva yang terhubung. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instansi tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen.

```cpp
class GraphicsPath : public System::Object
```

## Metode

| Method | Deskripsi |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Menambahkan busur elips yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Menambahkan busur elips yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Menambahkan busur elips yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Menambahkan busur elips yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Menambahkan kurva Bezier kubik yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Menambahkan kurva Bezier kubik yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Menambahkan kurva Bezier kubik yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Menambahkan kurva Bezier kubik yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Menambahkan urutan kurva Bezier kubik yang terhubung ke gambar saat ini. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Menambahkan urutan kurva Bezier kubik yang terhubung ke gambar saat ini. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Menambahkan kurva tertutup yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Menambahkan kurva tertutup yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Menambahkan kurva yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Menambahkan kurva yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Menambahkan kurva yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Menambahkan kurva yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Menambahkan elips yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Menambahkan elips yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Menambahkan elips yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Menambahkan elips yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Menambahkan garis yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Menambahkan garis yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddLine](./addline/)(int, int, int, int) | Menambahkan garis yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Menambahkan garis yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Menambahkan rangkaian segmen garis yang terhubung ke jalur yang diwakili oleh objek saat ini. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Menambahkan rangkaian segmen garis yang terhubung ke jalur yang diwakili oleh objek saat ini. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Menambahkan jalur yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Menambahkan kontur bentuk pai yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Menambahkan kontur bentuk pai yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Menambahkan kontur bentuk pai yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Menambahkan poligon yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Menambahkan poligon yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Menambahkan persegi panjang yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Menambahkan persegi panjang yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Menambahkan rangkaian persegi panjang yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Menambahkan rangkaian persegi panjang yang ditentukan ke jalur yang diwakili oleh objek saat ini. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Menambahkan rangkaian teks ke jalur yang diwakili oleh objek saat ini. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Menambahkan rangkaian teks ke jalur yang diwakili oleh objek saat ini. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Menambahkan rangkaian teks ke jalur yang diwakili oleh objek saat ini. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Menambahkan rangkaian teks ke jalur yang diwakili oleh objek saat ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Membuat salinan objek saat ini. |
| void [CloseAllFigures](./closeallfigures/)() | Menutup semua gambar terbuka dan memulai yang baru. |
| void [CloseFigure](./closefigure/)() | Menutup gambar saat ini dan memulai yang baru. |
| void [Dispose](./dispose/)() | Melepaskan semua sumber daya sistem operasi yang diperoleh oleh objek saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang ala C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang ala C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| void [Flatten](./flatten/)() | Mengubah setiap kurva dalam jalur menjadi serangkaian garis yang terhubung. Nilai kelandutan 0.25 digunakan. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Mengubah setiap kurva dalam jalur menjadi serangkaian garis yang terhubung. Nilai kelandutan 0.25 digunakan. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Mengubah setiap kurva dalam jalur menjadi serangkaian garis yang terhubung. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Mengembalikan mode isi dari objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Mengembalikan objek [PathData](../pathdata/) yang berisi titik-titik yang membentuk jalur yang diwakili oleh objek saat ini dan tipenya. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Mengembalikan array yang berisi titik-titik yang membentuk jalur yang diwakili oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Mengembalikan array yang berisi nilai yang menunjukkan tipe titik-titik yang membentuk jalur yang diwakili oleh objek saat ini. |
| int [get_PointCount](./get_pointcount/)() const | Mengembalikan jumlah titik dalam jalur yang diwakili oleh objek saat ini. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Mengembalikan objek [RectangleF](../../system.drawing/rectanglef/) yang mewakili persegi panjang yang membatasi jalur yang diwakili oleh objek saat ini ketika ditransformasikan dengan matriks yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Mengembalikan nilai yang merupakan kombinasi bitwise dari nilai Detail::FigureType yang menunjukkan tipe-tipe gambar yang terdapat dalam jalur yang diwakili oleh objek saat ini. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Mengembalikan objek [PointF](../../system.drawing/pointf/) yang mewakili titik terakhir pada jalur. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Membuat instansi baru dari kelas [GraphicsPath](./) dengan mode isi yang ditentukan. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Membuat instansi baru dari objek [GraphicsPath](./) yang mewakili jalur yang ditentukan. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Membuat instansi baru dari objek [GraphicsPath](./) yang mewakili jalur yang ditentukan. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](./) ini ketika digambar dengan [Pen](../../system.drawing/pen/) yang ditentukan. TIDAK DIIMPLEMENTASIKAN. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Menentukan apakah titik yang ditentukan berada di dalam jalur yang diwakili oleh objek saat ini. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Menentukan apakah titik yang ditentukan berada di dalam jalur yang diwakili oleh objek saat ini. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor penyalinan pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor penyalinan pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan nilai objek tipe nilai dengan nullptr berdasarkan referensi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [Reset](./reset/)() | Mengosongkan jalur dengan menghapus semua titik darinya. |
| void [Reverse](./reverse/)() | Membalik urutan titik dalam array PathPoints dari [GraphicsPath](./) ini. |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Mengatur mode isi dari objek saat ini. |
| void [SetMarkers](./setmarkers/)() | TIDAK DIIMPLEMENTASIKAN. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen templat ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [StartFigure](./startfigure/)() | Memulai gambar baru. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Mengubah jalur yang diwakili oleh objek saat ini dengan menerapkan matriks transformasi yang ditentukan. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembebasan pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Menggantikan jalur ini dengan kontur di sekitar jalur asli. |
|  [~GraphicsPath](./~graphicspath/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang Nama [System::Drawing::Drawing2D](../)
* Pustaka [Aspose.Slides](../../)