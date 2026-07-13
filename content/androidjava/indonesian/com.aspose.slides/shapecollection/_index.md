---
title: ShapeCollection
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili koleksi bentuk.
type: docs
url: /id/com.aspose.slides/shapecollection/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Mewakili koleksi bentuk.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi shape. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi shape. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Membuat diagram SmartArt dan menambahkannya ke akhir koleksi shape. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Membuat frame Zoom baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Membuat frame Zoom baru dengan gambar bawaan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Membuat frame Zoom Section baru dan menambahkannya ke akhir koleksi shape. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Membuat frame Zoom Section baru dengan gambar bawaan dan menambahkannya ke akhir koleksi shape. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Membuat frame Zoom Section baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Membuat frame Zoom Section baru dengan gambar bawaan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Membuat frame Zoom Summary baru dan menambahkannya ke akhir koleksi shape. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Membuat frame Zoom Summary baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Membuat frame objek OLE baru dan menambahkannya ke akhir koleksi shape. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Membuat frame objek OLE baru dan menambahkannya ke akhir koleksi shape. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Membuat frame objek OLE baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Membuat frame objek OLE baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Membuat frame video baru dan menambahkannya ke akhir koleksi shape. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Membuat frame video baru dan menambahkannya ke akhir koleksi shape. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Membuat frame video baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Membuat frame audio yang terhubung ke trek CD dan menambahkannya ke akhir koleksi shape. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Membuat frame audio yang terhubung ke trek CD dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Membuat frame audio yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi shape. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Membuat frame audio yang terhubung ke file audio eksternal dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Membuat frame audio dengan file WAV tersemat dan menambahkannya ke akhir koleksi shape. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Membuat frame audio dengan file WAV tersemat dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Membuat frame audio dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Membuat frame audio dan menyisipkannya ke koleksi shape pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Mengembalikan indeks berbasis nol dari kemunculan pertama shape yang ditentukan dalam koleksi. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array yang berisi semua shape. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array yang berisi semua shape dalam rentang yang ditentukan. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Memindahkan shapes yang ditentukan dalam koleksi shape, menempatkannya mulai dari indeks yang diberikan. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Membuat auto shape baru dan menambahkannya ke akhir koleksi shape, opsional menginisialisasinya dengan format templat default. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Membuat auto shape persegi panjang baru untuk menampung konten matematika dan menambahkannya ke akhir koleksi shape. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Membuat auto shape baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan, menerapkan format templat default. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Membuat auto shape baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan, opsional menginisialisasinya dengan gaya templat default. |
| [addGroupShape()](#addGroupShape--) | Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi shape. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Membuat grup shape baru, mengonversi gambar SVG yang ditentukan menjadi shape individu, dan menambahkannya ke akhir koleksi shape. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Membuat grup shape kosong baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Membuat connector shape baru dengan gaya templat default dan menambahkannya ke akhir koleksi shape. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Membuat connector shape baru dan menambahkannya ke akhir koleksi shape, opsional menerapkan gaya templat default. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Membuat connector shape baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan, menerapkan gaya templat default. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Membuat connector shape baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan, opsional menerapkan gaya templat default. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Membuat picture frame baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Membuat picture frame baru yang berisi gambar yang ditentukan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Membuat tabel baru dan menambahkannya ke akhir koleksi shape. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Membuat tabel baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus shape pada indeks yang ditentukan dari koleksi shape. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Menghapus kemunculan pertama shape yang ditentukan dari koleksi shape. |
| [clear()](#clear--) | Menghapus semua shape dari koleksi shape. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi melalui koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [getParentGroup()](#getParentGroup--) | Mendapatkan objek grup shape induk untuk koleksi shape. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Membuat salinan shape yang ditentukan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Membuat salinan shape yang ditentukan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Membuat salinan shape yang ditentukan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
### size() {#size--}
```
public final int size()
```

Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Baca-saja int .

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan. Baca-saja [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Membuat instance kelas Presentation yang mewakili file PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Mengakses slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Menambahkan chart dengan data defaultnya
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Mengatur judul chart
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Mengatur seri pertama untuk menampilkan nilai
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Mengatur indeks untuk lembar data chart
>      int defaultWorksheetIndex = 0;
>      // Mendapatkan lembar kerja data chart
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Menghapus seri dan kategori yang dihasilkan secara default
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Menambahkan seri baru
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Menambahkan kategori baru
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Mengambil seri chart pertama
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Mengisi data seri
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Mengatur warna isi untuk seri
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Mengambil seri chart kedua
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Mengisi data seri
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Mengatur warna isi untuk seri
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Mengatur label pertama untuk menampilkan nama Kategori
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Mengatur seri untuk menampilkan nilai pada label ketiga
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Menyimpan file PPTX ke disk
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Tipe chart yang akan ditambahkan. |
| x | float | Koordinat x chart baru, dalam poin. |
| y | float | Koordinat y chart baru, dalam poin. |
| width | float | Lebar chart, dalam poin. |
| height | float | Tinggi chart, dalam poin. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Tipe chart yang akan ditambahkan. |
| x | float | Koordinat x chart baru, dalam poin. |
| y | float | Koordinat y chart baru, dalam poin. |
| width | float | Lebar chart, dalam poin. |
| height | float | Tinggi chart, dalam poin. |
| initWithSample | boolean | True untuk menginisialisasi chart baru dengan data seri contoh dan pengaturan; false untuk membuat chart tanpa seri dan hanya pengaturan minimal, yang membuat pembuatan lebih cepat. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Membuat diagram SmartArt dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh berikut menunjukkan cara menambahkan smart shape dalam Presentasi PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x bingkai diagram, dalam poin. |
| y | float | Koordinat y bingkai diagram, dalam poin. |
| width | float | Lebar bingkai diagram, dalam poin. |
| height | float | Tinggi bingkai diagram, dalam poin. |
| layoutType | int | Tipe layout SmartArt. |

**Mengembalikan:**
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) yang baru dibuat.
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Tipe chart yang akan dibuat. |
| x | float | Koordinat x chart baru, dalam poin. |
| y | float | Koordinat y chart baru, dalam poin. |
| width | float | Lebar chart baru, dalam poin. |
| height | float | Tinggi chart baru, dalam poin. |
| index | int | Indeks berbasis nol tempat chart baru akan disisipkan dalam koleksi shape. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Tipe chart yang akan dibuat. |
| x | float | Koordinat x chart baru, dalam poin. |
| y | float | Koordinat y chart baru, dalam poin. |
| width | float | Lebar chart baru, dalam poin. |
| height | float | Tinggi chart baru, dalam poin. |
| index | int | Indeks berbasis nol tempat chart baru akan disisipkan dalam koleksi shape. |
| initWithSample | boolean | True untuk menginisialisasi chart baru dengan data seri contoh dan pengaturan; false untuk membuat chart tanpa seri dan hanya pengaturan minimal, yang membuat pembuatan lebih cepat. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Zoom ke akhir koleksi
>  (asumsi ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame Zoom baru, dalam poin. |
| y | float | Koordinat y frame Zoom baru, dalam poin. |
| width | float | Lebar frame Zoom baru, dalam poin. |
| height | float | Tinggi frame Zoom baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang dirujuk oleh frame Zoom; harus termasuk dalam presentasi ini. |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) yang baru dibuat.
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Zoom ke akhir koleksi
>  (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame Zoom baru, dalam poin. |
| y | float | Koordinat y frame Zoom baru, dalam poin. |
| width | float | Lebar frame Zoom baru, dalam poin. |
| height | float | Tinggi frame Zoom baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang dirujuk oleh frame Zoom; harus termasuk dalam presentasi ini. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar untuk slide yang dirujuk [IPPImage](../../com.aspose.slides/ippimage). |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) yang baru dibuat.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Membuat frame Zoom baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Zoom pada indeks yang ditentukan dalam sebuah koleksi
>  (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame Zoom akan disisipkan. |
| x | float | Koordinat x frame Zoom baru, dalam poin. |
| y | float | Koordinat y frame Zoom baru, dalam poin. |
| width | float | Lebar frame Zoom baru, dalam poin. |
| height | float | Tinggi frame Zoom baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang dirujuk oleh frame Zoom. |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) yang baru dibuat.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Membuat frame Zoom baru dengan gambar bawaan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Zoom pada indeks yang ditentukan dalam sebuah koleksi
>  (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame Zoom akan disisipkan. |
| x | float | Koordinat x frame Zoom baru, dalam poin. |
| y | float | Koordinat y frame Zoom baru, dalam poin. |
| width | float | Lebar frame Zoom baru, dalam poin. |
| height | float | Tinggi frame Zoom baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang dirujuk oleh frame Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar untuk slide yang dirujuk [IPPImage](../../com.aspose.slides/ippimage). |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) yang baru dibuat.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Membuat frame Zoom Section baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Section Zoom ke akhir koleksi
>  (asumsikan ada setidaknya dua section dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame Zoom Section baru, dalam poin. |
| y | float | Koordinat y frame Zoom Section baru, dalam poin. |
| width | float | Lebar frame Zoom Section baru, dalam poin. |
| height | float | Tinggi frame Zoom Section baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh frame Zoom Section; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Membuat frame Zoom Section baru dengan gambar bawaan dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Section Zoom ke akhir koleksi
>  (asumsikan ada setidaknya dua section dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame Zoom Section baru, dalam poin. |
| y | float | Koordinat y frame Zoom Section baru, dalam poin. |
| width | float | Lebar frame Zoom Section baru, dalam poin. |
| height | float | Tinggi frame Zoom Section baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh frame Zoom Section; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) yang akan ditampilkan dalam frame Zoom Section. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Membuat frame Zoom Section baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame Zoom Section akan disisipkan. |
| x | float | Koordinat x frame Zoom Section baru, dalam poin. |
| y | float | Koordinat y frame Zoom Section baru, dalam poin. |
| width | float | Lebar frame Zoom Section baru, dalam poin. |
| height | float | Tinggi frame Zoom Section baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh frame Zoom Section; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Membuat frame Zoom Section baru dengan gambar bawaan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Section Zoom pada indeks yang ditentukan dalam sebuah koleksi
>  (asumsikan ada setidaknya dua section dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame Zoom Section akan disisipkan. |
| x | float | Koordinat x frame Zoom Section baru, dalam poin. |
| y | float | Koordinat y frame Zoom Section baru, dalam poin. |
| width | float | Lebar frame Zoom Section baru, dalam poin. |
| height | float | Tinggi frame Zoom Section baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh frame Zoom Section; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar yang akan ditampilkan dalam frame Zoom Section. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Membuat frame Zoom Summary baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Summary Zoom ke akhir koleksi
>  (asumsikan ada setidaknya dua section dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame Zoom Summary baru, dalam poin. |
| y | float | Koordinat y frame Zoom Summary baru, dalam poin. |
| width | float | Lebar frame Zoom Summary baru, dalam poin. |
| height | float | Tinggi frame Zoom Summary baru, dalam poin. |

--------------------

Metode ini membuat Summary Zoom baru dan menempatkan koleksi objek di dalamnya untuk semua section dalam presentasi ini. |

**Mengembalikan:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) yang baru dibuat.
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Membuat frame Zoom Summary baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Summary Zoom pada indeks yang ditentukan dalam sebuah koleksi
>  (asumsikan ada setidaknya dua section dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame Zoom Summary akan disisipkan. |
| x | float | Koordinat x frame Zoom Summary baru, dalam poin. |
| y | float | Koordinat y frame Zoom Summary baru, dalam poin. |
| width | float | Lebar frame Zoom Summary baru, dalam poin. |
| height | float | Tinggi frame Zoom Summary baru, dalam poin. |

--------------------

Metode ini membuat frame Zoom Summary yang mengagregasikan tautan ringkasan untuk semua section dalam presentasi. |

**Mengembalikan:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) yang baru dibuat.
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Membuat frame objek OLE baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // Membuat instance kelas Presentation yang mewakili file PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Mengakses slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Memuat file Excel ke stream
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // Membuat objek data untuk disematkan
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Menambahkan shape Ole Object Frame
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Menulis PPTX ke disk
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame OLE baru, dalam poin. |
| y | float | Koordinat y frame OLE baru, dalam poin. |
| width | float | Lebar frame OLE baru, dalam poin. |
| height | float | Tinggi frame OLE baru, dalam poin. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informasi tentang data OLE yang disematkan ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Membuat frame objek OLE baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame OLE baru, dalam poin. |
| y | float | Koordinat y frame OLE baru, dalam poin. |
| width | float | Lebar frame OLE baru, dalam poin. |
| height | float | Tinggi frame OLE baru, dalam poin. |
| className | java.lang.String | Nama kelas objek OLE. |
| path | java.lang.String | Jalur ke file yang ditautkan.

Jalur ini disimpan persis dalam presentasi. Jika jalur relatif diberikan, file tidak akan dapat diakses saat membuka presentasi dari direktori berbeda. |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Membuat frame objek OLE baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame OLE akan disisipkan. |
| x | float | Koordinat x frame OLE baru, dalam poin. |
| y | float | Koordinat y frame OLE baru, dalam poin. |
| width | float | Lebar frame OLE baru, dalam poin. |
| height | float | Tinggi frame OLE baru, dalam poin. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informasi data OLE yang disematkan ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Membuat frame objek OLE baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame OLE akan disisipkan. |
| x | float | Koordinat x frame OLE baru, dalam poin. |
| y | float | Koordinat y frame OLE baru, dalam poin. |
| width | float | Lebar frame OLE baru, dalam poin. |
| height | float | Tinggi frame OLE baru, dalam poin. |
| className | java.lang.String | Nama kelas objek OLE. |
| path | java.lang.String | Jalur ke file yang ditautkan.

Jalur ini disimpan persis dalam presentasi. Jika jalur relatif diberikan, file tidak akan dapat diakses saat membuka presentasi dari direktori berbeda. |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Frame objek OLE yang baru dibuat.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Membuat frame video baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame video baru, dalam poin. |
| y | float | Koordinat y frame video baru, dalam poin. |
| width | float | Lebar frame video baru, dalam poin. |
| height | float | Tinggi frame video baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file video yang akan disematkan. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) yang baru dibuat.
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Membuat frame video baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame video baru, dalam poin. |
| y | float | Koordinat y frame video baru, dalam poin. |
| width | float | Lebar frame video baru, dalam poin. |
| height | float | Tinggi frame video baru, dalam poin. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) yang akan disematkan dalam frame video. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) yang baru dibuat.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Membuat frame video baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame video akan disisipkan. |
| x | float | Koordinat x frame video baru, dalam poin. |
| y | float | Koordinat y frame video baru, dalam poin. |
| width | float | Lebar frame video baru, dalam poin. |
| height | float | Tinggi frame video baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file video yang akan disematkan. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) yang baru dibuat.
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Membuat frame audio baru yang terhubung ke trek CD dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Membuat frame audio baru yang terhubung ke trek CD dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame audio akan disisipkan. |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Membuat frame audio baru yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file audio eksternal yang akan ditautkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Membuat frame audio baru yang terhubung ke file audio eksternal dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame audio akan disisipkan. |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file audio eksternal yang akan ditautkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Membuat frame audio baru dengan file WAV tersemat dan menambahkannya ke akhir koleksi shape. Audio yang disematkan ditambahkan ke koleksi Presentation.Audios.

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // Instantiates a presentation class that represents a presentation file
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Loads the the wav sound file to stream
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Adds the Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Sets the Play Mode and Volume of the Audio
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Writes the PowerPoint file to disk
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| audio_stream | java.io.InputStream | Aliran masukan yang berisi data audio WAV untuk disematkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Membuat frame audio baru dengan file WAV tersemat dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. Audio yang disematkan ditambahkan ke koleksi Presentation.Audios.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame audio akan disisipkan. |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| audio_stream | java.io.InputStream | Aliran masukan yang berisi data audio WAV untuk disematkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Membuat frame audio baru dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang ada dari daftar Presentation.Audios.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instansi [IAudio](../../com.aspose.slides/iaudio) dari koleksi Presentation.Audios. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Membuat frame audio baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat frame audio akan disisipkan. |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instansi [IAudio](../../com.aspose.slides/iaudio) dari koleksi Presentation.Audios untuk disematkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Mengembalikan indeks berbasis nol dari kemunculan pertama shape yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan dicari dalam koleksi. |

**Mengembalikan:**
int - Indeks berbasis nol dari kemunculan pertama shape dalam koleksi shape jika ditemukan; jika tidak, \\u20131.
### toArray() {#toArray--}
```
public ��  ? ?? ??? ??? ???  

```

Membuat dan mengembalikan array yang berisi semua shape.

**Mengembalikan:**
com.aspose.slides.IShape[] - Array objek [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Membuat dan mengembalikan array yang berisi semua shape dalam rentang yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Indeks shape pertama yang akan dikembalikan. |
| count | int | Jumlah shape yang akan dikembalikan. |

**Mengembalikan:**
com.aspose.slides.IShape[] - Array objek [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks target berbasis nol tempat shape akan ditempatkan. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dipindahkan dalam koleksi. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Memindahkan shapes yang ditentukan dalam koleksi shape, menempatkannya mulai dari indeks yang diberikan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks target berbasis nol tempat shape pertama yang ditentukan akan ditempatkan; shapes berikutnya mengikuti urutan yang diberikan. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Satu atau lebih instansi [IShape](../../com.aspose.slides/ishape) untuk dipindahkan dalam koleksi. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape yang akan ditambahkan. |
| x | float | Koordinat x bingkai shape, dalam poin. |
| y | float | Koordinat y bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat auto shape baru dan menambahkannya ke akhir koleksi shape, opsional menginisialisasinya dengan format templat default.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape yang akan ditambahkan. |
| x | float | Koordinat x bingkai shape, dalam poin. |
| y | float | Koordinat y bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya templat default (gaya sederhana, teks terpusat, dan nama tidak kosong) pada shape baru; false untuk membuat shape dengan semua properti diset ke nilai default. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Membuat auto shape persegi panjang baru untuk menampung konten matematika dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> The following example shows how to add Mathematical Equation in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x bingkai shape, dalam poin. |
| y | float | Koordinat y bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Membuat auto shape baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan, menerapkan format templat default.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat auto shape baru akan disisipkan. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape yang akan disisipkan. |
| x | float | Koordinat x bingkai shape, dalam poin. |
| y | float | Koordinat y bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public   … ?? … ??? ??? ??? ???  

```

Membuat auto shape baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan, opsional menginisialisasinya dengan gaya templat default.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat auto shape akan disisipkan. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape yang akan disisipkan. |
| x | float | Koordinat x bingkai shape, dalam poin. |
| y | float | Koordinat y bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya templat default (termasuk nama tidak kosong, gaya sederhana, dan teks terpusat); false untuk membuat shape dengan semua properti diset ke nilai default. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.
### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi shape. Bingkai grup akan otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.

--------------------

> ```
> Contoh berikut menunjukkan cara menambahkan grup shape ke slide dalam Presentasi PowerPoint.
>  
>  // Membuat instance kelas Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Mengambil slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Mengakses koleksi shape dari slide
>      IShapeCollection slideShapes = sld.getShapes();
>      // Menambahkan grup shape ke slide
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Menambahkan shape ke dalam grup shape yang ditambahkan
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Menambahkan bingkai grup shape
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Menulis file PPTX ke disk
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Membuat grup shape baru, mengonversi gambar SVG yang ditentukan menjadi shape individu, dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) yang berisi konten vektor untuk dikonversi menjadi shape. |
| x | float | Koordinat x bingkai grup, dalam poin. |
| y | float | Koordinat y bingkai grup, dalam poin. |
| width | float | Lebar bingkai grup, dalam poin. |
| height | float | Tinggi bingkai grup, dalam poin. |

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Membuat grup shape kosong baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. Bingkai grup akan otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat grup shape akan disisipkan. |

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Membuat connector shape baru dengan gaya templat default dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Membuat instance kelas presentasi yang mewakili file PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Mengakses koleksi shape untuk slide tertentu
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Menambahkan autoshape Ellipse
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Menambahkan autoshape Rectangle
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Menambahkan shape connector ke koleksi shape slide
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Menghubungkan shape menggunakan connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Memanggil reroute yang mengatur jalur terpendek otomatis antara shape
>      connector.reroute();
>      // Menyimpan presentasi
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape yang akan ditambahkan. |
| x | float | Koordinat x bingkai connector, dalam poin. |
| y | float | Koordinat y bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat connector shape baru dan menambahkannya ke akhir koleksi shape, opsional menerapkan gaya templat default.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape yang akan dibuat. |
| x | float | Koordinat x bingkai connector, dalam poin. |
| y | float | Koordinat y bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana); false untuk membuat connector dengan nilai properti default. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Membuat connector shape baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan, menerapkan gaya templat default.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat connector shape akan disisipkan. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape yang akan disisipkan. |
| x | float | Koordinat x bingkai connector, dalam poin. |
| y | float | Koordinat y bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat connector shape baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan, opsional menerapkan gaya templat default.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat connector shape akan disisipkan. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape yang akan disisipkan. |
| x | float | Koordinat x bingkai connector, dalam poin. |
| y | float | Koordinat y bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana); false untuk membuat connector dengan nilai properti default. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Membuat picture frame baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Menentukan tipe shape yang terkandung dalam [ShapeType](../../com.aspose.slides/shapetype), kecuali semua jenis garis:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | Koordinat x picture frame, dalam poin. |
| y | float | Koordinat y picture frame, dalam poin. |
| width | float | Lebar picture frame, dalam poin. |
| height | float | Tinggi picture frame, dalam poin. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) yang akan ditampilkan dalam picture frame. |

**Mengembalikan:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) yang baru dibuat.
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Membuat picture frame baru yang berisi gambar yang ditentukan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat picture frame akan disisipkan. |
| shapeType | int | Menentukan tipe shape yang terkandung dalam [ShapeType](../../com.aspose.slides/shapetype), kecuali semua jenis garis:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | Koordinat x picture frame, dalam poin. |
| y | float | Koordinat y picture frame, dalam poin. |
| width | float | Lebar picture frame, dalam poin. |
| height | float | Tinggi picture frame, dalam poin. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) yang akan ditampilkan dalam picture frame. |

**Mengembalikan:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) yang baru dibuat.
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Membuat tabel baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh berikut menunjukkan cara menambahkan tabel dalam Presentasi PowerPoint.
>  
>  // Membuat instance kelas Presentation yang mewakili file PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Mengakses slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Menentukan kolom dengan lebar dan baris dengan tinggi
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Menambahkan shape tabel ke slide
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Mengatur format border untuk setiap sel
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // Menggabungkan sel 1 & 2 pada baris 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Menambahkan teks ke sel yang digabungkan
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Menyimpan PPTX ke Disk
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x tabel, dalam poin. |
| y | float | Koordinat y tabel, dalam poin. |
| columnWidths | double[] | Array double yang mewakili lebar kolom tabel, dalam poin. |
| rowHeights | double[] | Array double yang mewakili tinggi baris tabel, dalam poin. |

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) yang baru dibuat.
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Membuat tabel baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat tabel akan disisipkan. |
| x | float | Koordinat x tabel, dalam poin. |
| y | float | Koordinat y tabel, dalam poin. |
| columnWidths | double[] | Array double yang mewakili lebar kolom tabel, dalam poin. |
| rowHeights | double[] | Array double yang mewakili tinggi baris tabel, dalam poin. |

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) yang baru dibuat.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus shape pada indeks yang ditentukan dari koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol shape yang akan dihapus. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Menghapus kemunculan pertama shape yang ditentukan dari koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dihapus. |

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua shape dari koleksi shape.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Mengembalikan enumerator yang mengiterasi melalui koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - IGenericEnumerator yang dapat digunakan untuk mengiterasi melalui koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator untuk seluruh koleksi.
### getParentGroup() {#getParentGroup--}
```
public   ??? ? ?? ??? ??? ??? 

```

Mendapatkan objek grup shape induk untuk koleksi shape. Baca-saja [IGroupShape](../../com.aspose.slides/igroupshape).

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan digandakan. |
| x | float | Koordinat x bingkai shape baru, dalam poin. |
| y | float | Koordinat y bingkai shape baru, dalam poin. |
| width | float | Lebar bingkai shape baru, dalam poin. |
| height | float | Tinggi bingkai shape baru, dalam poin. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. Shape baru mempertahankan lebar dan tinggi sourceShape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan digandakan. |
| x | float | Koordinat x bingkai shape baru, dalam poin. |
| y | float | Koordinat y bingkai shape baru, dalam poin. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. Shape yang digandakan mempertahankan posisi dan ukuran aslinya.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan digandakan. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Membuat salinan shape yang ditentukan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat shape yang digandakan akan disisipkan. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan digandakan. |
| x | float | Koordinat x bingkai shape yang digandakan, dalam poin. |
| y | float | Koordinat y bingkai shape yang digandakan, dalam poin. |
| width | float | Lebar bingkai shape yang digandakan, dalam poin. |
| height | float | Tinggi bingkai shape yang digandakan, dalam poin. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Membuat salinan shape yang ditentukan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. Shape baru mempertahankan lebar dan tinggi sourceShape.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat shape yang digandakan akan disisipkan. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan digandakan. |
| x | float | Koordinat x bingkai shape yang digandakan, dalam poin. |
| y | float | Koordinat y bingkai shape yang digandakan, dalam poin. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Membuat salinan shape yang ditentukan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan. Shape yang digandakan mempertahankan posisi dan ukuran aslinya.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat shape yang digandakan akan disisipkan. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan digandakan. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai di array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Baca-saja boolean .

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Baca-saja Object .

**Mengembalikan:**
java.lang.Object