---
title: IShapeCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi bentuk.
type: docs
url: /id/com.aspose.slides/ishapecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Mewakili koleksi shape.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [getParentGroup()](#getParentGroup--) | Mendapatkan objek grup shape induk untuk koleksi shape. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi shape. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi shape. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Membuat diagram SmartArt dan menambahkannya ke akhir koleksi shape. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Membuat bingkai Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Membuat bingkai Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Membuat bingkai Section Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Membuat bingkai Section Zoom baru dengan gambar yang telah ditentukan dan menambahkannya ke akhir koleksi shape. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Membuat bingkai Section Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Membuat bingkai Section Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Membuat bingkai Summary Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Membuat bingkai Summary Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi shape. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi shape. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Membuat bingkai video baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Membuat bingkai audio yang terhubung ke trek CD dan menambahkannya ke akhir koleksi shape. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Membuat bingkai audio yang terhubung ke trek CD dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Membuat bingkai audio yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi shape. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Membuat bingkai audio yang terhubung ke file audio eksternal dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Membuat bingkai audio dengan file WAV tersemat dan menambahkannya ke akhir koleksi shape. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Membuat bingkai audio baru dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Membuat bingkai audio dengan file WAV tersemat dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Membuat bingkai audio baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Mengembalikan indeks berbasis nol dari kemunculan pertama shape yang ditentukan dalam koleksi. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array yang berisi semua shape. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array yang berisi semua shape dalam rentang yang ditentukan. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Memindahkan shape yang ditentukan dalam koleksi shape, menempatkannya mulai dari indeks yang diberikan. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Membuat auto shape baru dan menambahkannya ke akhir koleksi shape, secara opsional menginisialisasinya dengan format template default. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Membuat auto shape persegi panjang baru untuk menampung konten matematika dan menambahkannya ke akhir koleksi shape. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, menerapkan format template default. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, secara opsional menginisialisasinya dengan gaya template default. |
| [addGroupShape()](#addGroupShape--) | Membuat group shape kosong baru dan menambahkannya ke akhir koleksi shape. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Membuat group shape baru, mengonversi gambar SVG yang ditentukan menjadi shape individual, dan menambahkan grup yang dihasilkan ke akhir koleksi shape. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Membuat group shape kosong baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Membuat connector shape baru dengan gaya template default dan menambahkannya ke akhir koleksi shape. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Membuat connector shape baru dan menambahkannya ke akhir koleksi shape, secara opsional menerapkan gaya template default. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Membuat connector shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, menerapkan gaya template default. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Membuat connector shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, secara opsional menerapkan gaya template default. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Membuat frame gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Membuat frame gambar baru yang berisi gambar yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Membuat tabel baru dan menambahkannya ke akhir koleksi shape. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Membuat tabel baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus shape pada indeks yang ditentukan dari koleksi shape. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Menghapus kemunculan pertama shape yang ditentukan dari koleksi shape. |
| [clear()](#clear--) | Menghapus semua shape dari koleksi shape. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Membuat salinan shape yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Membuat salinan shape yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Membuat salinan shape yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan. Baca-saja [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Mendapatkan objek grup shape induk untuk koleksi shape. Baca-saja [IGroupShape](../../com.aspose.slides/igroupshape).

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Jenis chart yang akan ditambahkan. |
| x | float | Koordinat x chart baru, dalam point. |
| y | float | Koordinat y chart baru, dalam point. |
| width | float | Lebar chart, dalam point. |
| height | float | Tinggi chart, dalam point. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Jenis chart yang akan ditambahkan. |
| x | float | Koordinat x chart baru, dalam point. |
| y | float | Koordinat y chart baru, dalam point. |
| width | float | Lebar chart, dalam point. |
| height | float | Tinggi chart, dalam point. |
| initWithSample | boolean | True untuk menginisialisasi chart baru dengan data seri contoh dan pengaturan; false untuk membuat chart tanpa seri dan hanya pengaturan minimal, yang mempercepat pembuatan. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Membuat diagram SmartArt dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x bingkai diagram, dalam point. |
| y | float | Koordinat y bingkai diagram, dalam point. |
| width | float | Lebar bingkai diagram, dalam point. |
| height | float | Tinggi bingkai diagram, dalam point. |
| layoutType | int | Jenis tata letak SmartArt. |

**Mengembalikan:**
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) yang baru dibuat.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Jenis chart yang akan dibuat. |
| x | float | Koordinat x chart baru, dalam point. |
| y | float | Koordinat y chart baru, dalam point. |
| width | float | Lebar chart baru, dalam point. |
| height | float | Tinggi chart baru, dalam point. |
| index | int | Indeks berbasis nol tempat menyisipkan chart baru dalam koleksi shape. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Jenis chart yang akan dibuat. |
| x | float | Koordinat x chart baru, dalam point. |
| y | float | Koordinat y chart baru, dalam point. |
| width | float | Lebar chart baru, dalam point. |
| height | float | Tinggi chart baru, dalam point. |
| index | int | Indeks berbasis nol tempat menyisipkan chart baru dalam koleksi shape. |
| initWithSample | boolean | True untuk menginisialisasi chart baru dengan data seri contoh dan pengaturan; false untuk membuat chart tanpa seri dan hanya pengaturan minimal, yang mempercepat pembuatan. |
| initWithSample | boolean | True untuk menginisialisasi chart baru dengan data dan pengaturan seri contoh; false untuk membuat chart tanpa seri dan hanya dengan pengaturan minimal, yang mempercepat pembuatan. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Membuat sebuah bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | float | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | float | Lebar bingkai OLE baru, dalam poin. |
| height | float | Tinggi bingkai OLE baru, dalam poin. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informasi data OLE yang tertanam ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Membuat sebuah bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | float | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | float | Lebar bingkai OLE baru, dalam poin. |
| height | float | Tinggi bingkai OLE baru, dalam poin. |
| className | java.lang.String | Nama kelas objek OLE. |
| path | java.lang.String | Jalur ke file yang ditautkan.  

Jalur ini disimpan apa adanya dalam presentasi. Jika jalur relatif ditentukan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda. |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Membuat sebuah bingkai objek OLE baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bingkai objek OLE. |
| x | float | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | float | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | float | Lebar bingkai OLE baru, dalam poin. |
| height | float | Tinggi bingkai OLE baru, dalam poin. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informasi data OLE yang tertanam ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Membuat sebuah bingkai objek OLE baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bingkai objek OLE. |
| x | float | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | float | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | float | Lebar bingkai OLE baru, dalam poin. |
| height | float | Tinggi bingkai OLE baru, dalam poin. |
| className | java.lang.String | Nama kelas objek OLE. |
| path | java.lang.String | Jalur ke file yang ditautkan.  

Jalur ini disimpan apa adanya dalam presentasi. Jika jalur relatif ditentukan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda. |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Membuat sebuah bingkai Zoom baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Zoom ke akhir koleksi
>  (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari bingkai Zoom baru, dalam poin. |
| y | float | Koordinat y dari bingkai Zoom baru, dalam poin. |
| width | float | Lebar bingkai Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Zoom baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang direferensikan oleh bingkai Zoom; harus milik presentasi ini. |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Membuat sebuah bingkai Zoom baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Zoom ke akhir koleksi
>  (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari bingkai Zoom baru, dalam poin. |
| y | float | Koordinat y dari bingkai Zoom baru, dalam poin. |
| width | float | Lebar bingkai Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Zoom baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang direferensikan oleh bingkai Zoom; harus milik presentasi ini. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar untuk slide yang direferensikan [IPPImage](../../com.aspose.slides/ippimage). |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Membuat sebuah bingkai Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan cara membuat dan menyisipkan objek Zoom pada indeks tertentu dalam sebuah koleksi
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bingkai Zoom. |
| x | float | Koordinat x dari bingkai Zoom baru, dalam poin. |
| y | float | Koordinat y dari bingkai Zoom baru, dalam poin. |
| width | float | Lebar bingkai Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Zoom baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang direferensikan oleh bingkai Zoom. |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Membuat sebuah bingkai Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Zoom pada indeks tertentu dalam sebuah koleksi
>  (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bingkai Zoom. |
| x | float | Koordinat x dari bingkai Zoom baru, dalam poin. |
| y | float | Koordinat y dari bingkai Zoom baru, dalam poin. |
| width | float | Lebar bingkai Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Zoom baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang direferensikan oleh bingkai Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar untuk slide yang direferensikan [IPPImage](../../com.aspose.slides/ippimage). |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Membuat sebuah bingkai Section Zoom baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Section Zoom ke akhir sebuah koleksi
>  (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari bingkai Section Zoom baru, dalam poin. |
| y | float | Koordinat y dari bingkai Section Zoom baru, dalam poin. |
| width | float | Lebar bingkai Section Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang direferensikan oleh bingkai Section Zoom; harus milik presentasi ini dan berisi setidaknya satu slide. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Membuat sebuah bingkai Section Zoom baru dengan gambar yang telah ditentukan dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Section Zoom ke akhir sebuah koleksi
>  (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari bingkai Section Zoom baru, dalam poin. |
| y | float | Koordinat y dari bingkai Section Zoom baru, dalam poin. |
| width | float | Lebar bingkai Section Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang direferensikan oleh bingkai Section Zoom; harus milik presentasi ini dan berisi setidaknya satu slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) yang akan ditampilkan dalam bingkai Section Zoom. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Membuat sebuah bingkai Section Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Section Zoom pada indeks tertentu dalam sebuah koleksi
>  (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bingkai Section Zoom. |
| x | float | Koordinat x dari bingkai Section Zoom baru, dalam poin. |
| y | float | Koordinat y dari bingkai Section Zoom baru, dalam poin. |
| width | float | Lebar bingkai Section Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang direferensikan oleh bingkai Section Zoom; harus milik presentasi ini dan berisi setidaknya satu slide. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Membuat sebuah bingkai Section Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Section Zoom pada indeks tertentu dalam sebuah koleksi
>  (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bingkai Section Zoom. |
| x | float | Koordinat x dari bingkai Section Zoom baru, dalam poin. |
| y | float | Koordinat y dari bingkai Section Zoom baru, dalam poin. |
| width | float | Lebar bingkai Section Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang direferensikan oleh bingkai Section Zoom; harus milik presentasi ini dan berisi setidaknya satu slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar yang akan ditampilkan dalam bingkai Section Zoom. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Membuat sebuah bingkai Summary Zoom baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini menunjukkan cara menambahkan objek Summary Zoom ke akhir sebuah koleksi
>  (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari bingkai Summary Zoom baru, dalam poin. |
| y | float | Koordinat y dari bingkai Summary Zoom baru, dalam poin. |
| width | float | Lebar bingkai Summary Zoom baru, dalam poin. |
| height | float | Tinggi bingkai Summary Zoom baru, dalam poin. |
Metode ini membuat sebuah Summary Zoom frame yang mengumpulkan tautan ringkasan untuk semua bagian dalam presentasi. |

**Mengembalikan:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - yang baru dibuat [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Membuat sebuah Summary Zoom frame baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini menunjukkan pembuatan dan penyisipan objek Summary Zoom pada indeks tertentu dalam sebuah koleksi
>  (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dimana Summary Zoom frame akan disisipkan. |
| x | float | Koordinat x dari Summary Zoom frame baru, dalam poin. |
| y | float | Koordinat y dari Summary Zoom frame baru, dalam poin. |
| width | float | Lebar dari Summary Zoom frame baru, dalam poin. |
| height | float | Tinggi dari Summary Zoom frame baru, dalam poin. |

--------------------

Metode ini membuat sebuah Summary Zoom frame yang mengumpulkan tautan ringkasan untuk semua bagian dalam presentasi. |

**Mengembalikan:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - yang baru dibuat [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Membuat sebuah frame video baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame video baru, dalam poin. |
| y | float | Koordinat y dari frame video baru, dalam poin. |
| width | float | Lebar dari frame video baru, dalam poin. |
| height | float | Tinggi dari frame video baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file video yang akan disematkan. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - yang baru dibuat [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Membuat sebuah frame video baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame video baru, dalam poin. |
| y | float | Koordinat y dari frame video baru, dalam poin. |
| width | float | Lebar dari frame video baru, dalam poin. |
| height | float | Tinggi dari frame video baru, dalam poin. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) yang akan disematkan dalam frame video. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - yang baru dibuat [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Membuat sebuah frame video baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dimana frame video akan disisipkan. |
| x | float | Koordinat x dari frame video baru, dalam poin. |
| y | float | Koordinat y dari frame video baru, dalam poin. |
| width | float | Lebar dari frame video baru, dalam poin. |
| height | float | Tinggi dari frame video baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file video yang akan disematkan. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - yang baru dibuat [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Membuat sebuah frame audio baru yang terhubung ke trek CD dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - yang baru dibuat [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Membuat sebuah frame audio baru yang terhubung ke trek CD dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dimana frame audio akan disisipkan. |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - yang baru dibuat [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Membuat sebuah frame audio baru yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file audio eksternal yang akan ditautkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - yang baru dibuat [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Membuat sebuah frame audio baru yang terhubung ke file audio eksternal dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dimana frame audio akan disisipkan. |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file audio eksternal yang akan ditautkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - yang baru dibuat [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Membuat sebuah frame audio baru dengan file WAV yang disematkan dan menambahkannya ke akhir koleksi shape. Audio yang disematkan ditambahkan ke koleksi Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| audio_stream | java.io.InputStream | Aliran masukan yang berisi data audio WAV untuk disematkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - yang baru dibuat [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Membuat sebuah frame audio baru dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang sudah ada dari daftar Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instansi [IAudio](../../com.aspose.slides/iaudio) dari koleksi Presentation.Audios. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - yang baru dibuat [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Membuat sebuah frame audio baru dengan file WAV yang disematkan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. Audio yang disematkan ditambahkan ke koleksi Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dimana frame audio akan disisipkan. |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| audio_stream | java.io.InputStream | Aliran masukan yang berisi data audio WAV untuk disematkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - yang baru dibuat [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Membuat sebuah frame audio baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan menggunakan objek audio yang sudah ada dari daftar Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dimana frame audio akan ditempatkan. |
| x | float | Koordinat x dari frame audio baru, dalam poin. |
| y | float | Koordinat y dari frame audio baru, dalam poin. |
| width | float | Lebar dari frame audio baru, dalam poin. |
| height | float | Tinggi dari frame audio baru, dalam poin. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instansi [IAudio](../../com.aspose.slides/iaudio) dari koleksi Presentation.Audios untuk disematkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - yang baru dibuat [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
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
public abstract IShape[] toArray()
```

Membuat dan mengembalikan sebuah array yang berisi semua shape.

**Mengembalikan:**
com.aspose.slides.IShape[] - Sebuah array objek [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Membuat dan mengembalikan sebuah array yang berisi semua shape dalam rentang yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Indeks shape pertama yang akan dikembalikan. |
| count | int | Jumlah shape yang akan dikembalikan. |

**Mengembalikan:**
com.aspose.slides.IShape[] - Sebuah array objek [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target berbasis nol dimana shape akan ditempatkan. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dipindahkan dalam koleksi. |
### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Memindahkan shape yang ditentukan dalam koleksi shape, menempatkannya mulai dari indeks yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target berbasis nol dimana shape pertama yang ditentukan akan ditempatkan; shape selanjutnya mengikuti urutan yang diberikan. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Satu atau lebih [IShape](../../com.aspose.slides/ishape) untuk dipindahkan dalam koleksi. |
### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Membuat sebuah auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari auto shape yang akan ditambahkan.
| x | float | Koordinat x dari bingkai shape, dalam poin. |
| y | float | Koordinat y dari bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat auto shape baru dan menambahkannya ke akhir koleksi shape, secara opsional menginisialisasinya dengan format templat default.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari auto shape yang akan ditambahkan. |
| x | float | Koordinat x dari bingkai shape, dalam poin. |
| y | float | Koordinat y dari bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya templat default (gaya sederhana, teks terpusat, dan nama tidak kosong) pada shape baru; false untuk membuat shape dengan semua properti diatur ke nilai default mereka. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Membuat rectangle auto shape baru untuk menampung konten matematis dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari bingkai shape, dalam poin. |
| y | float | Koordinat y dari bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Membuat auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, menerapkan format templat default.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan auto shape baru. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari auto shape yang akan disisipkan. |
| x | float | Koordinat x dari bingkai shape, dalam poin. |
| y | float | Koordinat y dari bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, secara opsional menginisialisasinya dengan gaya templat default.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan auto shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari auto shape yang akan disisipkan. |
| x | float | Koordinat x dari bingkai shape, dalam poin. |
| y | float | Koordinat y dari bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya templat default (termasuk nama tidak kosong, gaya sederhana, dan teks terpusat); false untuk membuat shape dengan semua properti diatur ke nilai default mereka. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Membuat group shape kosong baru dan menambahkannya ke akhir koleksi shape. Bingkai grup akan otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Membuat group shape baru, mengonversi gambar SVG yang ditentukan menjadi shape individu, dan menambahkan grup yang dihasilkan ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) yang berisi konten vektor untuk dikonversi menjadi shape. |
| x | float | Koordinat x dari bingkai grup, dalam poin. |
| y | float | Koordinat y dari bingkai grup, dalam poin. |
| width | float | Lebar bingkai grup, dalam poin. |
| height | float | Tinggi bingkai grup, dalam poin. |

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Membuat group shape kosong baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. Bingkai grup akan otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan group shape. |

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Membuat connector shape baru dengan gaya templat default dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari connector shape yang akan ditambahkan. |
| x | float | Koordinat x dari bingkai connector, dalam poin. |
| y | float | Koordinat y dari bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat connector shape baru dan menambahkannya ke akhir koleksi shape, secara opsional menerapkan gaya templat default.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari connector shape yang akan dibuat. |
| x | float | Koordinat x dari bingkai connector, dalam poin. |
| y | float | Koordinat y dari bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana); false untuk membuat connector dengan nilai properti default. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Membuat connector shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, menerapkan gaya templat default.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari connector shape yang akan disisipkan. |
| x | float | Koordinat x dari bingkai connector, dalam poin. |
| y | float | Koordinat y dari bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat connector shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, secara opsional menerapkan gaya templat default.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) dari connector shape yang akan disisipkan. |
| x | float | Koordinat x dari bingkai connector, dalam poin. |
| y | float | Koordinat y dari bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana); false untuk membuat connector dengan nilai properti default. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Membuat picture frame baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| shapeType | int | Menentukan jenis shape yang terdapat dalam [ShapeType](../../com.aspose.slides/shapetype), kecuali semua jenis garis:

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
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Membuat picture frame baru yang berisi gambar yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan picture frame. |
| shapeType | int | Menentukan jenis shape yang terdapat dalam [ShapeType](../../com.aspose.slides/shapetype), kecuali semua jenis garis:

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
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Membuat tabel baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari tabel, dalam poin. |
| y | float | Koordinat y dari tabel, dalam poin. |
| columnWidths | double[] | Array double yang mewakili lebar kolom tabel, dalam poin. |
| rowHeights | double[] | Array double yang mewakili tinggi baris tabel, dalam poin. |

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) yang baru dibuat.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Membuat tabel baru dan menyisipkannya ke koleksi bentuk pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan tabel. |
| x | float | Koordinat x tabel, dalam poin. |
| y | float | Koordinat y tabel, dalam poin. |
| columnWidths | double[] | Array double yang merepresentasikan lebar kolom tabel, dalam poin. |
| rowHeights | double[] | Array double yang merepresentasikan tinggi baris tabel, dalam poin. |

**Return:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) yang baru dibuat.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus bentuk pada indeks yang ditentukan dari koleksi bentuk.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari bentuk yang akan dihapus. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Menghapus kemunculan pertama dari bentuk yang ditentukan dari koleksi bentuk.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua bentuk dari koleksi bentuk.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Bentuk yang akan dikloning. |
| x | float | Koordinat x frame bentuk yang dikloning, dalam poin. |
| y | float | Koordinat y frame bentuk yang dikloning, dalam poin. |
| width | float | Lebar frame bentuk yang dikloning, dalam poin. |
| height | float | Tinggi frame bentuk yang dikloning, dalam poin. |

**Return:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Bentuk baru mempertahankan lebar dan tinggi dari sourceShape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dikloning. |
| x | float | Koordinat x frame bentuk yang dikloning, dalam poin. |
| y | float | Koordinat y frame bentuk yang dikloning, dalam poin. |

**Return:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Bentuk yang dikloning mempertahankan posisi dan ukuran asli.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dikloning. |

**Return:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dikloning. |
| x | float | Koordinat x frame bentuk yang dikloning, dalam poin. |
| y | float | Koordinat y frame bentuk yang dikloning, dalam poin. |
| width | float | Lebar frame bentuk yang dikloning, dalam poin. |
| height | float | Tinggi frame bentuk yang dikloning, dalam poin. |

**Return:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk baru mempertahankan lebar dan tinggi dari sourceShape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dikloning. |
| x | float | Koordinat x frame bentuk yang dikloning, dalam poin. |
| y | float | Koordinat y frame bentuk yang dikloning, dalam poin. |

**Return:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk yang dikloning mempertahankan posisi dan ukuran asli.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dikloning. |

**Return:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.