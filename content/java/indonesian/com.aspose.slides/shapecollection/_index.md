---
title: ShapeCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan bentuk.
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

Mewakili sebuah koleksi bentuk.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Membuat diagram SmartArt dan menambahkannya ke akhir koleksi bentuk. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Membuat bingkai Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Membuat bingkai Zoom baru dengan gambar pra-definisi dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Membuat bingkai Zoom Seksi baru dan menambahkannya ke akhir koleksi bentuk. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Membuat bingkai Zoom Seksi baru dengan gambar pra-definisi dan menambahkannya ke akhir koleksi bentuk. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Membuat bingkai Zoom Seksi baru dan menyisipkannya ke koleksi bentuk pada indeks yang ditentukan. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Membuat bingkai Zoom Seksi baru dengan gambar pra-definisi dan menyisipkannya ke koleksi bentuk pada indeks yang ditentukan. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Membuat bingkai Zoom Ringkasan baru dan menambahkannya ke akhir koleksi bentuk. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Membuat bingkai Zoom Ringkasan baru dan menyisipkannya ke koleksi bentuk pada indeks yang ditentukan. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Membuat bingkai video baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Membuat bingkai audio yang terhubung ke trek CD dan menambahkannya ke akhir koleksi bentuk. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Membuat bingkai audio yang terhubung ke trek CD dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Membuat bingkai audio yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi bentuk. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Membuat bingkai audio yang terhubung ke file audio eksternal dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Membuat bingkai audio dengan file WAV tersemat dan menambahkannya ke akhir koleksi bentuk. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Membuat bingkai audio dengan file WAV tersemat dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Membuat bingkai audio baru dan menambahkannya ke akhir koleksi bentuk menggunakan objek audio yang sudah ada dari daftar Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Membuat bingkai audio baru dan menyisipkannya ke koleksi bentuk pada indeks yang ditentukan menggunakan objek audio yang sudah ada dari daftar Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Mengembalikan indeks berbasis nol dari kemunculan pertama bentuk yang ditentukan dalam koleksi. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array yang berisi semua bentuk. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array yang berisi semua bentuk dalam rentang yang ditentukan. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Memindahkan bentuk yang ditentukan ke posisi baru dalam koleksi bentuk. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Memindahkan bentuk-bentuk yang ditentukan dalam koleksi bentuk, menempatkannya mulai dari indeks yang diberikan. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Membuat auto shape baru dengan pemformatan default dan menambahkannya ke akhir koleksi bentuk. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Membuat auto shape baru dan menambahkannya ke akhir koleksi bentuk, secara opsional menginisialisasinya dengan pemformatan template default. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Membuat auto shape persegi panjang baru untuk menampung konten matematis dan menambahkannya ke akhir koleksi bentuk. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, menerapkan pemformatan template default. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, secara opsional menginisialisasinya dengan gaya template default. |
| [addGroupShape()](#addGroupShape--) | Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi bentuk. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Membuat grup shape baru, mengonversi gambar SVG yang ditentukan menjadi bentuk-bentuk individu, dan menambahkannya ke akhir koleksi bentuk. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Membuat grup shape kosong baru dan menyisipkannya ke koleksi bentuk pada indeks yang ditentukan. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Membuat shape penghubung baru dengan gaya template default dan menambahkannya ke akhir koleksi bentuk. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Membuat shape penghubung baru dan menambahkannya ke akhir koleksi bentuk, secara opsional menerapkan gaya template default. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Membuat shape penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, menerapkan gaya template default. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Membuat shape penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, secara opsional menerapkan gaya template default. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Membuat tabel baru dan menambahkannya ke akhir koleksi bentuk. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Membuat tabel baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus bentuk pada indeks yang ditentukan dari koleksi bentuk. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Menghapus kemunculan pertama bentuk yang ditentukan dari koleksi bentuk. |
| [clear()](#clear--) | Menghapus semua bentuk dari koleksi bentuk. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi melalui koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [getParentGroup()](#getParentGroup--) | Mendapatkan objek grup shape induk untuk koleksi bentuk. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |

### size() {#size--}
```
public final int size()
```


Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. **Baca-saja**  int .

**Mengembalikan:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan. **Baca-saja** [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```


Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Membuat instance kelas Presentation yang merepresentasikan file PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Mengakses slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Menambahkan grafik dengan data default-nya
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Mengatur judul grafik
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Mengatur seri pertama agar menunjukkan nilai
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Mengatur indeks untuk lembar data grafik
>      int defaultWorksheetIndex = 0;
>      // Mendapatkan lembar kerja data grafik
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
>      // Mengambil seri grafik pertama
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Mengisi data seri
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Mengatur warna isi untuk seri
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Mengambil seri grafik kedua
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Mengisi data seri
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Mengatur warna isi untuk seri
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Mengatur label pertama agar menampilkan nama Kategori
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Mengatur seri agar menampilkan nilai untuk label ketiga
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Jenis bagan yang akan ditambahkan. |
| x | float | Koordinat x bagan baru, dalam poin. |
| y | float | Koordinat y bagan baru, dalam poin. |
| width | float | Lebar bagan, dalam poin. |
| height | float | Tinggi bagan, dalam poin. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```


Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Jenis bagan yang akan ditambahkan. |
| x | float | Koordinat x bagan baru, dalam poin. |
| y | float | Koordinat y bagan baru, dalam poin. |
| width | float | Lebar bagan, dalam poin. |
| height | float | Tinggi bagan, dalam poin. |
| initWithSample | boolean | True untuk menginisialisasi bagan baru dengan data seri contoh dan pengaturan; false untuk membuat bagan tanpa seri dan hanya pengaturan minimal, sehingga pembuatan lebih cepat. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```


Membuat diagram SmartArt dan menambahkannya ke akhir koleksi bentuk.

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x bingkai diagram, dalam poin. |
| y | float | Koordinat y bingkai diagram, dalam poin. |
| width | float | Lebar bingkai diagram, dalam poin. |
| height | float | Tinggi bingkai diagram, dalam poin. |
| layoutType | int | Jenis tata letak SmartArt. |

**Mengembalikan:**
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) yang baru dibuat.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```


Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Jenis bagan yang akan dibuat. |
| x | float | Koordinat x bagan baru, dalam poin. |
| y | float | Koordinat y bagan baru, dalam poin. |
| width | float | Lebar bagan baru, dalam poin. |
| height | float | Tinggi bagan baru, dalam poin. |
| index | int | Indeks berbasis nol tempat bagan baru akan disisipkan dalam koleksi bentuk. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```


Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Jenis bagan yang akan dibuat. |
| x | float | Koordinat x dari chart baru, dalam poin. |
| y | float | Koordinat y dari chart baru, dalam poin. |
| width | float | Lebar chart baru, dalam poin. |
| height | float | Tinggi chart baru, dalam poin. |
| index | int | Indeks berbasis nol tempat menyisipkan chart baru dalam koleksi shape. |
| initWithSample | boolean | True untuk menginisialisasi chart baru dengan data dan pengaturan contoh; false untuk membuat chart tanpa seri dan hanya pengaturan minimal, yang mempercepat pembuatan. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Membuat Zoom frame baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| x | float | Koordinat x dari Zoom frame baru, dalam poin. |
| y | float | Koordinat y dari Zoom frame baru, dalam poin. |
| width | float | Lebar Zoom frame baru, dalam poin. |
| height | float | Tinggi Zoom frame baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang dirujuk oleh Zoom frame; harus merupakan bagian dari presentasi ini. |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) yang baru dibuat.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Membuat Zoom frame baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| x | float | Koordinat x dari Zoom frame baru, dalam poin. |
| y | float | Koordinat y dari Zoom frame baru, dalam poin. |
| width | float | Lebar Zoom frame baru, dalam poin. |
| height | float | Tinggi Zoom frame baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang dirujuk oleh Zoom frame; harus merupakan bagian dari presentasi ini. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar untuk slide yang dirujuk [IPPImage](../../com.aspose.slides/ippimage). |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) yang baru dibuat.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Membuat Zoom frame baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Zoom pada indeks tertentu dalam sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
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
| index | int | Indeks berbasis nol tempat menyisipkan Zoom frame. |
| x | float | Koordinat x dari Zoom frame baru, dalam poin. |
| y | float | Koordinat y dari Zoom frame baru, dalam poin. |
| width | float | Lebar Zoom frame baru, dalam poin. |
| height | float | Tinggi Zoom frame baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang dirujuk oleh Zoom frame. |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) yang baru dibuat.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Membuat Zoom frame baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Zoom pada indeks tertentu dalam sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
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
| index | int | Indeks berbasis nol tempat menyisipkan Zoom frame. |
| x | float | Koordinat x dari Zoom frame baru, dalam poin. |
| y | float | Koordinat y dari Zoom frame baru, dalam poin. |
| width | float | Lebar Zoom frame baru, dalam poin. |
| height | float | Tinggi Zoom frame baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang dirujuk oleh Zoom frame. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar untuk slide yang dirujuk [IPPImage](../../com.aspose.slides/ippimage). |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) yang baru dibuat.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Membuat Section Zoom frame baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan penambahan objek Section Zoom ke akhir sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
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
| x | float | Koordinat x dari Section Zoom frame baru, dalam poin. |
| y | float | Koordinat y dari Section Zoom frame baru, dalam poin. |
| width | float | Lebar Section Zoom frame baru, dalam poin. |
| height | float | Tinggi Section Zoom frame baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh Section Zoom frame; harus merupakan bagian dari presentasi ini dan berisi setidaknya satu slide. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Membuat Section Zoom frame baru dengan gambar yang telah ditentukan dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan penambahan objek Section Zoom ke akhir sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x dari Section Zoom frame baru, dalam poin. |
| y | float | Koordinat y dari Section Zoom frame baru, dalam poin. |
| width | float | Lebar Section Zoom frame baru, dalam poin. |
| height | float | Tinggi Section Zoom frame baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh Section Zoom frame; harus merupakan bagian dari presentasi ini dan berisi setidaknya satu slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) yang akan ditampilkan dalam Section Zoom frame. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```
Membuat bingkai Section Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Section Zoom pada indeks tertentu dalam sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
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
| index | int | Indeks berbasis nol tempat menyisipkan bingkai Section Zoom. |
| x | float | Koordinat x bingkai Section Zoom baru, dalam poin. |
| y | float | Koordinat y bingkai Section Zoom baru, dalam poin. |
| width | float | Lebar bingkai Section Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang direferensikan oleh bingkai Section Zoom; harus milik presentasi ini dan berisi setidaknya satu slide. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Membuat bingkai Section Zoom baru dengan gambar bawaan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Section Zoom pada indeks tertentu dalam sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bingkai Section Zoom. |
| x | float | Koordinat x bingkai Section Zoom baru, dalam poin. |
| y | float | Koordinat y bingkai Section Zoom baru, dalam poin. |
| width | float | Lebar bingkai Section Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang direferensikan oleh bingkai Section Zoom; harus milik presentasi ini dan berisi setidaknya satu slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar yang akan ditampilkan di dalam bingkai Section Zoom. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Membuat bingkai Summary Zoom baru dan menambahkannya ke akhir koleksi bentuk.

--------------------

> ```
> Contoh ini menunjukkan penambahan objek Summary Zoom ke akhir sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
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
| x | float | Koordinat x bingkai Summary Zoom baru, dalam poin. |
| y | float | Koordinat y bingkai Summary Zoom baru, dalam poin. |
| width | float | Lebar bingkai Summary Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Summary Zoom baru, dalam poin. |

--------------------

Metode ini membuat Summary Zoom baru dan menempatkan sekumpulan objek di dalamnya untuk semua bagian dalam presentasi ini. |

**Mengembalikan:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) yang baru dibuat.
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Membuat bingkai Summary Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Summary Zoom pada indeks tertentu dalam sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
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
| index | int | Indeks berbasis nol tempat menyisipkan bingkai Summary Zoom. |
| x | float | Koordinat x bingkai Summary Zoom baru, dalam poin. |
| y | float | Koordinat y bingkai Summary Zoom baru, dalam poin. |
| width | float | Lebar bingkai Summary Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Summary Zoom baru, dalam poin. |

--------------------

Metode ini membuat bingkai Summary Zoom yang mengagregasi tautan ringkasan untuk semua bagian dalam presentasi. |

**Mengembalikan:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) yang baru dibuat.
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk.

--------------------

> ```
> Contoh berikut menunjukkan cara menambahkan OLE Object Frame ke slide presentasi PowerPoint.
>  
// Membuat instance kelas Presentation yang merepresentasikan PPTX
Presentation pres = new Presentation();
try
{
    // Mengakses slide pertama
    ISlide sld = pres.getSlides().get_Item(0);

    // Memuat file cel ke dalam stream
    FileInputStream fs = new FileInputStream("book1.xlsx");
    ByteArrayOutputStream mstream = new ByteArrayOutputStream();
    byte[] buf = new byte[4096];

    while (true)
    {
        int bytesRead = fs.read(buf, 0, buf.length);
        if (bytesRead <= 0)
            break;
        mstream.write(buf, 0, bytesRead);
    }
    // Membuat objek data untuk penyematan
    IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");

    // Menambahkan shape Ole Object Frame
    IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
            (float)pres.getSlideSize().getSize().getHeight(), dataInfo);

    // Menulis PPTX ke disk
    pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
}
catch (IOException e) { }
finally
{
    if (pres != null) pres.dispose();
}
```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x bingkai OLE baru, dalam poin. |
| y | float | Koordinat y bingkai OLE baru, dalam poin. |
| width | float | Lebar bingkai OLE baru, dalam poin. |
| height | float | Tinggi bingkai OLE baru, dalam poin. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informasi tentang data OLE yang disematkan ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Koordinat x bingkai OLE baru, dalam poin. |
| y | float | Koordinat y bingkai OLE baru, dalam poin. |
| width | float | Lebar bingkai OLE baru, dalam poin. |
| height | float | Tinggi bingkai OLE baru, dalam poin. |
| className | java.lang.String | Nama kelas objek OLE. |
| path | java.lang.String | Path ke file yang ditautkan.

Path ini disimpan persis dalam presentasi. Jika path relatif ditentukan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda. |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan cara menyisipkan objek OLE pada indeks kedua:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bingkai objek OLE. |
| x | float | Koordinat x dari frame OLE baru, dalam poin. |
| y | float | Koordinat y dari frame OLE baru, dalam poin. |
| width | float | Lebar dari frame OLE baru, dalam poin. |
| height | float | Tinggi dari frame OLE baru, dalam poin. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informasi data OLE yang disematkan ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Membuat frame objek OLE baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan frame objek OLE. |
| x | float | Koordinat x dari frame OLE baru, dalam poin. |
| y | float | Koordinat y dari frame OLE baru, dalam poin. |
| width | float | Lebar dari frame OLE baru, dalam poin. |
| height | float | Tinggi dari frame OLE baru, dalam poin. |
| className | java.lang.String | Nama kelas dari objek OLE. |
| path | java.lang.String | Path ke file yang ditautkan.

Path ini disimpan persis dalam presentasi. Jika path relatif ditentukan, file akan tidak dapat diakses saat membuka presentasi dari direktori yang berbeda. |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Frame objek OLE yang baru dibuat.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Membuat frame video baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame video baru, dalam poin. |
| y | float | Koordinat y dari frame video baru, dalam poin. |
| width | float | Lebar dari frame video baru, dalam poin. |
| height | float | Tinggi dari frame video baru, dalam poin. |
| fname | java.lang.String | Path atau nama file video yang akan disematkan. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) yang baru dibuat.
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Membuat frame video baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame video baru, dalam poin. |
| y | float | Koordinat y dari frame video baru, dalam poin. |
| width | float | Lebar dari frame video baru, dalam poin. |
| height | float | Tinggi dari frame video baru, dalam poin. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) yang akan disematkan dalam frame video. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) yang baru dibuat.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Membuat frame video baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan frame video. |
| x | float | Koordinat x dari frame video baru, dalam poin. |
| y | float | Koordinat y dari frame video baru, dalam poin. |
| width | float | Lebar dari frame video baru, dalam poin. |
| height | float | Tinggi dari frame video baru, dalam poin. |
| fname | java.lang.String | Path atau nama file video yang akan disematkan. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) yang baru dibuat.
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Membuat frame audio baru yang terhubung ke trek CD dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Membuat frame audio baru yang terhubung ke trek CD dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan frame audio. |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Membuat frame audio baru yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| fname | java.lang.String | Path atau nama file audio eksternal yang akan ditautkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Membuat frame audio baru yang terhubung ke file audio eksternal dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan frame audio. |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| fname | java.lang.String | Path atau nama file audio eksternal yang akan ditautkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Membuat frame audio baru dengan file WAV yang disematkan dan menambahkannya ke akhir koleksi shape. Audio yang disematkan ditambahkan ke koleksi Presentation.Audios.

--------------------

> ```
> Contoh berikut menunjukkan cara membuat Audio Frame.
>  
>  // Membuat instance kelas Presentation yang merepresentasikan file presentasi
>  Presentation pres = new Presentation();
>  try {
>      // Mendapatkan slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Memuat file wav ke dalam stream
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Menambahkan Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Mengatur Mode Pemutaran dan Volume Audio
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Menulis file PowerPoint ke disk
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| audio_stream | java.io.InputStream | Aliran masukan yang berisi data audio WAV untuk disematkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Membuat frame audio baru dengan file WAV yang disematkan dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. Audio yang disematkan ditambahkan ke koleksi Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan frame audio. |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| audio_stream | java.io.InputStream | Aliran masukan yang berisi data audio WAV untuk disematkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Membuat frame audio baru dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang ada dari daftar Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instansi [IAudio](../../com.aspose.slides/iaudio) dari koleksi Presentation.Audios. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Membuat frame audio baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan frame audio. |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instansi [IAudio](../../com.aspose.slides/iaudio) dari koleksi Presentation.Audios untuk disematkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Mengembalikan indeks berbasis nol dari kejadian pertama shape yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan dicari dalam koleksi. |

**Mengembalikan:**
int - Indeks berbasis nol dari kejadian pertama shape dalam koleksi shape jika ditemukan; jika tidak, \\u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target berbasis nol tempat shape akan ditempatkan. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dipindahkan dalam koleksi. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Memindahkan shapes yang ditentukan dalam koleksi shape, menempatkannya mulai dari indeks yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target berbasis nol tempat shape pertama yang ditentukan akan ditempatkan; shapes berikutnya akan mengikuti urutan yang diberikan. |
| bentuk | [IShape\[\]](../../com.aspose.slides/ishape) | Satu atau lebih [IShape](../../com.aspose.slides/ishape) instance untuk dipindahkan dalam koleksi. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Membuat sebuah auto shape baru dengan pemformatan default dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari auto shape yang akan ditambahkan. |
| x | float | Koordinat x dari frame shape, dalam poin. |
| y | float | Koordinat y dari frame shape, dalam poin. |
| width | float | Lebar frame shape, dalam poin. |
| height | float | Tinggi frame shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat sebuah auto shape baru dan menambahkannya ke akhir koleksi shape, dengan opsional menginisialisasinya dengan pemformatan template default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari auto shape yang akan ditambahkan. |
| x | float | Koordinat x dari frame shape, dalam poin. |
| y | float | Koordinat y dari frame shape, dalam poin. |
| width | float | Lebar frame shape, dalam poin. |
| height | float | Tinggi frame shape, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya template default (gaya sederhana, teks terpusat, dan nama tidak kosong) pada shape baru; false untuk membuat shape dengan semua properti disetel ke nilai defaultnya. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Membuat sebuah auto shape persegi panjang baru untuk menampung konten matematis dan menambahkannya ke akhir koleksi shape.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame shape, dalam poin. |
| y | float | Koordinat y dari frame shape, dalam poin. |
| width | float | Lebar frame shape, dalam poin. |
| height | float | Tinggi frame shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Membuat sebuah auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, dengan menerapkan pemformatan template default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan auto shape baru. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari auto shape yang akan disisipkan. |
| x | float | Koordinat x dari frame shape, dalam poin. |
| y | float | Koordinat y dari frame shape, dalam poin. |
| width | float | Lebar frame shape, dalam poin. |
| height | float | Tinggi frame shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat sebuah auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, dengan opsional menginisialisasinya dengan gaya template default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan auto shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari auto shape yang akan disisipkan. |
| x | float | Koordinat x dari frame shape, dalam poin. |
| y | float | Koordinat y dari frame shape, dalam poin. |
| width | float | Lebar frame shape, dalam poin. |
| height | float | Tinggi frame shape, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya template default (termasuk nama tidak kosong, gaya sederhana, dan teks terpusat); false untuk membuat shape dengan semua properti disetel ke nilai defaultnya. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Membuat sebuah group shape kosong baru dan menambahkannya ke akhir koleksi shape. Frame grup akan secara otomatis menyesuaikan untuk menampung semua shape yang ditambahkan.

--------------------

> ```
> Contoh berikut menunjukkan cara menambahkan grup shape ke slide presentasi PowerPoint.
>  
>  // Membuat instance kelas Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Mengakses slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Mengakses koleksi shape pada slide
>      IShapeCollection slideShapes = sld.getShapes();
>      // Menambahkan group shape ke slide
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Menambahkan shape di dalam group shape yang ditambahkan
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Menambahkan frame group shape
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

Membuat sebuah group shape baru, mengkonversi gambar SVG yang ditentukan menjadi shape individu, dan menambahkan grup yang dihasilkan ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) yang berisi konten vektor untuk dikonversi menjadi shape. |
| x | float | Koordinat x dari frame grup, dalam poin. |
| y | float | Koordinat y dari frame grup, dalam poin. |
| width | float | Lebar frame grup, dalam poin. |
| height | float | Tinggi frame grup, dalam poin. |

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Membuat sebuah group shape kosong baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. Frame grup akan secara otomatis menyesuaikan untuk menampung semua shape yang ditambahkan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan group shape. |

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Membuat sebuah connector shape baru dengan gaya template default dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Instantiates a presentation class that represents a PPTX file
>  Presentation pres = new Presentation();
>  try {
>      // Accesses the shapes collection for a specific slide
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Adds an Ellipse autoshape
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Adds a Rectangle autoshape
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Adds a connector shape to the slide shape collection
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Connects the shapes using the connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Calls reroute that sets the automatic shortest path between shapes
>      connector.reroute();
>      // Saves the presentation
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari connector shape yang akan ditambahkan. |
| x | float | Koordinat x dari frame connector, dalam poin. |
| y | float | Koordinat y dari frame connector, dalam poin. |
| width | float | Lebar frame connector, dalam poin. |
| height | float | Tinggi frame connector, dalam poin. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat sebuah connector shape baru dan menambahkannya ke akhir koleksi shape, dengan opsional menerapkan gaya template default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari connector shape yang akan dibuat. |
| x | float | Koordinat x dari frame connector, dalam poin. |
| y | float | Koordinat y dari frame connector, dalam poin. |
| width | float | Lebar frame connector, dalam poin. |
| height | float | Tinggi frame connector, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya template default (nama tidak kosong, gaya sederhana); false untuk membuat connector dengan nilai properti default. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Membuat sebuah connector shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, dengan menerapkan gaya template default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari connector shape yang akan disisipkan. |
| x | float | Koordinat x dari frame connector, dalam poin. |
| y | float | Koordinat y dari frame connector, dalam poin. |
| width | float | Lebar frame connector, dalam poin. |
| height | float | Tinggi frame connector, dalam poin. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat sebuah connector shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, dengan opsional menerapkan gaya template default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari connector shape yang akan disisipkan. |
| x | float | Koordinat x dari frame connector, dalam poin. |
| y | float | Koordinat y dari frame connector, dalam poin. |
| width | float | Lebar frame connector, dalam poin. |
| height | float | Tinggi frame connector, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya template default (nama tidak kosong, gaya sederhana); false untuk membuat connector dengan nilai properti default. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Membuat sebuah picture frame baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | int | Menentukan jenis shape yang terkandung dalam [ShapeType](../../com.aspose.slides/shapetype), kecuali semua jenis garis:

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
| x | float | Koordinat x dari picture frame, dalam poin. |
| y | float | Koordinat y dari picture frame, dalam poin. |
| width | float | Lebar picture frame, dalam poin. |
| height | float | Tinggi picture frame, dalam poin. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) untuk ditampilkan dalam picture frame. |

**Mengembalikan:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) yang baru dibuat.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Membuat sebuah picture frame baru yang berisi gambar yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan picture frame. |
| shapeType | int | Menentukan jenis shape yang terkandung dalam [ShapeType](../../com.aspose.slides/shapetype), kecuali semua jenis garis:

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
| x | float | Koordinat x dari picture frame, dalam poin. |
| y | float | Koordinat y dari picture frame, dalam poin. |
| width | float | Lebar picture frame, dalam poin. |
| height | float | Tinggi picture frame, dalam poin. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) untuk ditampilkan dalam picture frame. |

**Mengembalikan:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) yang baru dibuat.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Membuat sebuah tabel baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh berikut menunjukkan cara menambahkan tabel dalam Presentasi PowerPoint.
>  
>  // Membuat instance kelas Presentation yang merepresentasikan file PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Mengakses slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Mendefinisikan kolom dengan lebar dan baris dengan tinggi
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Menambahkan shape tabel ke slide
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Mengatur format border untuk tiap sel
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
>      // Menyimpan PPTX ke disk
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari tabel, dalam poin. |
| y | float | Koordinat y dari tabel, dalam poin. |
| columnWidths | double[] | Array double yang mewakili lebar kolom tabel, dalam poin. |
| rowHeights | double[] | Array double yang mewakili tinggi baris tabel, dalam poin. |

**Mengembalikan:**  
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) yang baru dibuat.  
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Membuat tabel baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat tabel disisipkan. |
| x | float | Koordinat x dari tabel, dalam poin. |
| y | float | Koordinat y dari tabel, dalam poin. |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari shape yang akan dihapus. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Menghapus keberadaan pertama dari shape yang ditentukan dari koleksi shape.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
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

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.  
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator untuk seluruh koleksi.  
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Mendapatkan objek shape grup induk untuk koleksi shape. Baca-saja [IGroupShape](../../com.aspose.slides/igroupshape).

**Mengembalikan:**  
[IGroupShape](../../com.aspose.slides/igroupshape)  
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan digandakan. |
| x | float | Koordinat x dari frame shape baru, dalam poin. |
| y | float | Koordinat y dari frame shape baru, dalam poin. |
| width | float | Lebar frame shape baru, dalam poin. |
| height | float | Tinggi frame shape baru, dalam poin. |

**Mengembalikan:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.  
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. Shape baru mempertahankan lebar dan tinggi dari sourceShape .

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan digandakan. |
| x | float | Koordinat x dari frame shape baru, dalam poin. |
| y | float | Koordinat y dari frame shape baru, dalam poin. |

**Mengembalikan:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.  
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. Shape yang digandakan mempertahankan posisi dan ukuran asli.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan digandakan. |

**Mengembalikan:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.  
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Membuat salinan shape yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat shape yang digandakan disisipkan. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan digandakan. |
| x | float | Koordinat x dari frame shape yang digandakan, dalam poin. |
| y | float | Koordinat y dari frame shape yang digandakan, dalam poin. |
| width | float | Lebar frame shape yang digandakan, dalam poin. |
| height | float | Tinggi frame shape yang digandakan, dalam poin. |

**Mengembalikan:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.  
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Membuat salinan shape yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. Shape baru mempertahankan lebar dan tinggi dari sourceShape .

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat shape yang digandakan disisipkan. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan digandakan. |
| x | float | Koordinat x dari frame shape yang digandakan, dalam poin. |
| y | float | Koordinat y dari frame shape yang digandakan, dalam poin. |

**Mengembalikan:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.  
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Membuat salinan shape yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. Shape yang digandakan mempertahankan posisi dan ukuran asli.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat shape yang digandakan disisipkan. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan digandakan. |

**Mengembalikan:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.  
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai di array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). Baca-saja boolean.

**Mengembalikan:**  
boolean  
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan root sinkronisasi. Baca-saja Object.

**Mengembalikan:**  
java.lang.Object