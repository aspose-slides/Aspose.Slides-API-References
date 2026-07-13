---
title: IShapeCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili kumpulan shape.
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
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Membuat frame objek OLE baru dan menambahkannya ke akhir koleksi shape. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Membuat frame objek OLE baru dan menambahkannya ke akhir koleksi shape. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Membuat frame objek OLE baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Membuat frame objek OLE baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Membuat frame Zoom baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Membuat frame Zoom baru dengan gambar pra-definisi dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Membuat frame Section Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Membuat frame Section Zoom baru dengan gambar pra-definisi dan menambahkannya ke akhir koleksi shape. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Membuat frame Section Zoom baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Membuat frame Section Zoom baru dengan gambar pra-definisi dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Membuat frame Summary Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Membuat frame Summary Zoom baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Membuat frame video baru dan menambahkannya ke akhir koleksi shape. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Membuat frame video baru dan menambahkannya ke akhir koleksi shape. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Membuat frame video baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Membuat frame audio yang terhubung ke trek CD dan menambahkannya ke akhir koleksi shape. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Membuat frame audio yang terhubung ke trek CD dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Membuat frame audio yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi shape. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Membuat frame audio yang terhubung ke file audio eksternal dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Membuat frame audio dengan file WAV tertanam dan menambahkannya ke akhir koleksi shape. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Membuat frame audio dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Membuat frame audio dengan file WAV tertanam dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Membuat frame audio dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Mengembalikan indeks berbasis-nol dari kemunculan pertama shape yang ditentukan dalam koleksi. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array yang berisi semua shape. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array yang berisi semua shape dalam rentang yang ditentukan. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Memindahkan shapes yang ditentukan dalam koleksi shape, menempatkannya mulai dari indeks yang diberikan. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Membuat auto shape baru dan menambahkannya ke akhir koleksi shape, opsional menginisialisasinya dengan format templat default. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Membuat rectangle auto shape baru untuk menampung konten matematika dan menambahkannya ke akhir koleksi shape. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Membuat auto shape baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan, menerapkan format templat default. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Membuat auto shape baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan, opsional menginisialisasinya dengan styling templat default. |
| [addGroupShape()](#addGroupShape--) | Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi shape. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Membuat grup shape baru, mengonversi gambar SVG yang ditentukan menjadi shape terpisah, dan menambahkannya ke akhir koleksi shape. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Membuat grup shape kosong baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Membuat shape konektor baru dengan styling templat default dan menambahkannya ke akhir koleksi shape. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Membuat shape konektor baru dan menambahkannya ke akhir koleksi shape, opsional menerapkan styling templat default. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Membuat shape konektor baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan, menerapkan styling templat default. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Membuat shape konektor baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan, opsional menerapkan styling templat default. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Membuat frame gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Membuat frame gambar baru yang berisi gambar yang ditentukan dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Membuat tabel baru dan menambahkannya ke akhir koleksi shape. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Membuat tabel baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus shape pada indeks yang ditentukan dari koleksi shape. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Menghapus kemunculan pertama shape yang ditentukan dari koleksi shape. |
| [clear()](#clear--) | Menghapus semua shape dari koleksi shape. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Membuat salinan shape yang ditentukan dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Membuat salinan shape yang ditentukan dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Membuat salinan shape yang ditentukan dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. |

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
| type | int | Tipe chart yang akan ditambahkan. |
| x | float | Koordinat x chart baru, dalam poin. |
| y | float | Koordinat y chart baru, dalam poin. |
| width | float | Lebar chart, dalam poin. |
| height | float | Tinggi chart, dalam poin. |

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
| x | float | Koordinat x bingkai diagram, dalam poin. |
| y | float | Koordinat y bingkai diagram, dalam poin. |
| width | float | Lebar bingkai diagram, dalam poin. |
| height | float | Tinggi bingkai diagram, dalam poin. |
| layoutType | int | Tipe tata letak SmartArt. |

**Mengembalikan:**
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) yang baru dibuat.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Tipe chart yang akan dibuat. |
| x | float | Koordinat x chart baru, dalam poin. |
| y | float | Koordinat y chart baru, dalam poin. |
| width | float | Lebar chart baru, dalam poin. |
| height | float | Tinggi chart baru, dalam poin. |
| index | int | Indeks berbasis-nol tempat chart baru akan dimasukkan ke dalam koleksi shape. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Tipe chart yang akan dibuat. |
| x | float | Koordinat x chart baru, dalam poin. |
| y | float | Koordinat y chart baru, dalam poin. |
| width | float | Lebar chart baru, dalam poin. |
| height | float | Tinggi chart baru, dalam poin. |
| index | int | Indeks berbasis-nol tempat chart baru akan dimasukkan ke dalam koleksi shape. |
| initWithSample | boolean | True untuk menginisialisasi chart baru dengan data seri contoh dan pengaturan; false untuk membuat chart tanpa seri dan hanya pengaturan minimal, yang membuat pembuatan lebih cepat. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) yang baru dibuat.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Membuat frame objek OLE baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x frame OLE baru, dalam poin. |
| y | float | Koordinat y frame OLE baru, dalam poin. |
| width | float | Lebar frame OLE baru, dalam poin. |
| height | float | Tinggi frame OLE baru, dalam poin. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informasi data OLE tertanam ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Membuat frame objek OLE baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x frame OLE baru, dalam poin. |
| y | float | Koordinat y frame OLE baru, dalam poin. |
| width | float | Lebar frame OLE baru, dalam poin. |
| height | float | Tinggi frame OLE baru, dalam poin. |
| className | java.lang.String | Nama kelas objek OLE. |
| path | java.lang.String | Jalur ke file yang ditautkan.

Jalur ini disimpan persis dalam presentasi. Jika jalur relatif diberikan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda. |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Membuat frame objek OLE baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat frame objek OLE akan dimasukkan. |
| x | float | Koordinat x frame OLE baru, dalam poin. |
| y | float | Koordinat y frame OLE baru, dalam poin. |
| width | float | Lebar frame OLE baru, dalam poin. |
| height | float | Tinggi frame OLE baru, dalam poin. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informasi data OLE tertanam ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Membuat frame objek OLE baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat frame objek OLE akan dimasukkan. |
| x | float | Koordinat x frame OLE baru, dalam poin. |
| y | float | Koordinat y frame OLE baru, dalam poin. |
| width | float | Lebar frame OLE baru, dalam poin. |
| height | float | Tinggi frame OLE baru, dalam poin. |
| className | java.lang.String | Nama kelas objek OLE. |
| path | java.lang.String | Jalur ke file yang ditautkan.

Jalur ini disimpan persis dalam presentasi. Jika jalur relatif diberikan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda. |

**Mengembalikan:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) yang baru dibuat.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape.

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
| Parameter | Tipe | Deskripsi |
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
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini memperlihatkan penambahan objek Zoom ke akhir koleksi
>  (asumsikan bahwa ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
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
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Membuat frame Zoom baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| index | int | Indeks berbasis-nol tempat frame Zoom akan dimasukkan. |
| x | float | Koordinat x frame Zoom baru, dalam poin. |
| y | float | Koordinat y frame Zoom baru, dalam poin. |
| width | float | Lebar frame Zoom baru, dalam poin. |
| height | float | Tinggi frame Zoom baru, dalam poin. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) yang dirujuk oleh frame Zoom. |

**Mengembalikan:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) yang baru dibuat.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Membuat frame Zoom baru dengan gambar pra-definisi dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini memperlihatkan pembuatan dan penyisipan objek Zoom pada indeks yang ditentukan dalam sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua slide dalam presentasi "Presentation.pptx"):
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
| index | int | Indeks berbasis-nol tempat frame Zoom akan dimasukkan. |
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
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Membuat frame Section Zoom baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini memperlihatkan penambahan objek Section Zoom ke akhir koleksi
>  (asumsikan bahwa ada setidaknya dua seksi dalam presentasi "Presentation.pptx"):
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
| x | float | Koordinat x frame Section Zoom baru, dalam poin. |
| y | float | Koordinat y frame Section Zoom baru, dalam poin. |
| width | float | Lebar frame Section Zoom baru, dalam poin. |
| height | float | Tinggi frame Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh frame Section Zoom; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Membuat frame Section Zoom baru dengan gambar pra-definisi dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> Contoh ini memperlihatkan penambahan objek Section Zoom ke akhir koleksi
>  (asumsikan bahwa ada setidaknya dua seksi dalam presentasi "Presentation.pptx"):
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x frame Section Zoom baru, dalam poin. |
| y | float | Koordinat y frame Section Zoom baru, dalam poin. |
| width | float | Lebar frame Section Zoom baru, dalam poin. |
| height | float | Tinggi frame Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh frame Section Zoom; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) yang akan ditampilkan di dalam frame Section Zoom. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Membuat frame Section Zoom baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini memperlihatkan pembuatan dan penyisipan objek Section Zoom pada indeks yang ditentukan dalam sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua seksi dalam presentasi "Presentation.pptx"):
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
| index | int | Indeks berbasis-nol tempat frame Section Zoom akan dimasukkan. |
| x | float | Koordinat x frame Section Zoom baru, dalam poin. |
| y | float | Koordinat y frame Section Zoom baru, dalam poin. |
| width | float | Lebar frame Section Zoom baru, dalam poin. |
| height | float | Tinggi frame Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh frame Section Zoom; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Membuat frame Section Zoom baru dengan gambar pra-definisi dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> Contoh ini memperlihatkan pembuatan dan penyisipan objek Section Zoom pada indeks yang ditentukan dalam sebuah koleksi
>  (asumsikan bahwa ada setidaknya dua seksi dalam presentasi "Presentation.pptx"):
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
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat frame Section Zoom akan dimasukkan. |
| x | float | Koordinat x frame Section Zoom baru, dalam poin. |
| y | float | Koordinat y frame Section Zoom baru, dalam poin. |
| width | float | Lebar frame Section Zoom baru, dalam poin. |
| height | float | Tinggi frame Section Zoom baru, dalam poin. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) yang dirujuk oleh frame Section Zoom; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Gambar yang akan ditampilkan dalam frame Section Zoom. |

**Mengembalikan:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) yang baru dibuat.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Membuat frame Summary Zoom baru dan menambahkannya ke akhir koleksi shape.

--------------------

> ```
> This example demonstrates adding a Summary Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| x | float | Koordinat x frame Summary Zoom baru, dalam poin. |
| y | float | Koordinat y frame Summary Zoom baru, dalam poin. |
| width | float | Lebar frame Summary Zoom baru, dalam poin. |
| height | float | Tinggi frame Summary Zoom baru, dalam poin. |

--------------------

Metode ini membuat frame Summary Zoom yang mengagregasi tautan ringkasan untuk semua seksi dalam presentasi. |

**Mengembalikan:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) yang baru dibuat.

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Membuat frame Summary Zoom baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

--------------------

> ```
> This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| index | int | Indeks berbasis-nol tempat frame Summary Zoom akan dimasukkan. |
| x | float | Koordinat x frame Summary Zoom baru, dalam poin. |
| y | float | Koordinat y frame Summary Zoom baru, dalam poin. |
| width | float | Lebar frame Summary Zoom baru, dalam poin. |
| height | float | Tinggi frame Summary Zoom baru, dalam poin. |

--------------------

Metode ini membuat frame Summary Zoom yang mengagregasi tautan ringkasan untuk semua seksi dalam presentasi. |

**Mengembalikan:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) yang baru dibuat.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Membuat frame video baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x frame video baru, dalam poin. |
| y | float | Koordinat y frame video baru, dalam poin. |
| width | float | Lebar frame video baru, dalam poin. |
| height | float | Tinggi frame video baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file video yang akan ditanamkan. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) yang baru dibuat.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Membuat frame video baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x frame video baru, dalam poin. |
| y | float | Koordinat y frame video baru, dalam poin. |
| width | float | Lebar frame video baru, dalam poin. |
| height | float | Tinggi frame video baru, dalam poin. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) yang akan ditanamkan dalam frame video. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) yang baru dibuat.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Membuat frame video baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat frame video akan dimasukkan. |
| x | float | Koordinat x frame video baru, dalam poin. |
| y | float | Koordinat y frame video baru, dalam poin. |
| width | float | Lebar frame video baru, dalam poin. |
| height | float | Tinggi frame video baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file video yang akan ditanamkan. |

**Mengembalikan:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) yang baru dibuat.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Membuat frame audio baru yang terhubung ke trek CD dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Membuat frame audio baru yang terhubung ke trek CD dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat frame audio akan dimasukkan. |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Membuat frame audio baru yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
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
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Membuat frame audio baru yang terhubung ke file audio eksternal dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat frame audio akan dimasukkan. |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| fname | java.lang.String | Jalur atau nama file audio eksternal yang akan ditautkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Membuat frame audio baru dengan file WAV tertanam dan menambahkannya ke akhir koleksi shape. Audio tertanam ditambahkan ke koleksi Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| audio_stream | java.io.InputStream | Aliran masuk yang berisi data audio WAV untuk ditanamkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Membuat frame audio baru dan menambahkannya ke akhir koleksi shape menggunakan objek audio yang ada dari daftar Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instansi [IAudio](../../com.aspose.slides/iaudio) dari koleksi Presentation.Audios. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Membuat frame audio baru dengan file WAV tertanam dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. Audio tertanam ditambahkan ke koleksi Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat frame audio akan dimasukkan. |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| audio_stream | java.io.InputStream | Aliran masuk yang berisi data audio WAV untuk ditanamkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Membuat frame audio baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat frame audio akan dimasukkan. |
| x | float | Koordinat x frame audio baru, dalam poin. |
| y | float | Koordinat y frame audio baru, dalam poin. |
| width | float | Lebar frame audio baru, dalam poin. |
| height | float | Tinggi frame audio baru, dalam poin. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instansi [IAudio](../../com.aspose.slides/iaudio) dari koleksi Presentation.Audios untuk ditanamkan. |

**Mengembalikan:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) yang baru dibuat.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Mengembalikan indeks berbasis-nol dari kemunculan pertama shape yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan dicari dalam koleksi. |

**Mengembalikan:**
int - Indeks berbasis-nol dari kemunculan pertama shape dalam koleksi shape jika ditemukan; jika tidak, \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Membuat dan mengembalikan array yang berisi semua shape.

**Mengembalikan:**
com.aspose.slides.IShape[] - Array objek [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
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
public abstract void reorder(int index, IShape shape)
```

Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target berbasis-nol tempat shape akan ditempatkan. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dipindahkan dalam koleksi. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Memindahkan shapes yang ditentukan dalam koleksi shape, menempatkannya mulai dari indeks yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks target berbasis-nol tempat shape pertama yang ditentukan akan ditempatkan; shape selanjutnya mengikuti urutan yang diberikan. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Satu atau lebih instansi [IShape](../../com.aspose.slides/ishape) untuk dipindahkan dalam koleksi. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
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
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat auto shape baru dan menambahkannya ke akhir koleksi shape, opsional menginisialisasinya dengan format templat default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape yang akan ditambahkan. |
| x | float | Koordinat x bingkai shape, dalam poin. |
| y | float | Koordinat y bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan styling templat default (gaya sederhana, teks terpusat, dan nama tidak kosong) pada shape baru; false untuk membuat shape dengan semua properti diatur ke nilai default mereka. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Membuat rectangle auto shape baru untuk menampung konten matematika dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x bingkai shape, dalam poin. |
| y | float | Koordinat y bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Membuat auto shape baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan, menerapkan format templat default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat auto shape baru akan dimasukkan. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape yang akan dimasukkan. |
| x | float | Koordinat x bingkai shape, dalam poin. |
| y | float | Koordinat y bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat auto shape baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan, opsional menginisialisasinya dengan styling templat default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat auto shape akan dimasukkan. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape yang akan dimasukkan. |
| x | float | Koordinat x bingkai shape, dalam poin. |
| y | float | Koordinat y bingkai shape, dalam poin. |
| width | float | Lebar bingkai shape, dalam poin. |
| height | float | Tinggi bingkai shape, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan styling templat default (termasuk nama tidak kosong, gaya sederhana, dan teks terpusat); false untuk membuat shape dengan semua properti diatur ke nilai default mereka. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) yang baru dibuat.

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi shape. Bingkai grup akan otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Membuat grup shape baru, mengonversi gambar SVG yang ditentukan menjadi shape terpisah, dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
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
public abstract IGroupShape insertGroupShape(int index)
```

Membuat grup shape kosong baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. Bingkai grup akan otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat grup shape akan dimasukkan. |

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) yang baru dibuat.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Membuat connector shape baru dengan styling templat default dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
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
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat connector shape baru dan menambahkannya ke akhir koleksi shape, opsional menerapkan styling templat default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape yang akan dibuat. |
| x | float | Koordinat x bingkai connector, dalam poin. |
| y | float | Koordinat y bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan styling templat default (nama tidak kosong, gaya sederhana); false untuk membuat connector dengan nilai properti default. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Membuat connector shape baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan, menerapkan styling templat default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat connector shape akan dimasukkan. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape yang akan dimasukkan. |
| x | float | Koordinat x bingkai connector, dalam poin. |
| y | float | Koordinat y bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Membuat connector shape baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan, opsional menerapkan styling templat default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat connector shape akan dimasukkan. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape yang akan dimasukkan. |
| x | float | Koordinat x bingkai connector, dalam poin. |
| y | float | Koordinat y bingkai connector, dalam poin. |
| width | float | Lebar bingkai connector, dalam poin. |
| height | float | Tinggi bingkai connector, dalam poin. |
| createFromTemplate | boolean | True untuk menerapkan styling templat default (nama tidak kosong, gaya sederhana); false untuk membuat connector dengan nilai properti default. |

**Mengembalikan:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) yang baru dibuat.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Membuat picture frame baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
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
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Membuat picture frame baru yang berisi gambar yang ditentukan dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat picture frame akan dimasukkan. |
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
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Membuat tabel baru dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x tabel, dalam poin. |
| y | float | Koordinat y tabel, dalam poin. |
| columnWidths | double[] | Array double yang mewakili lebar kolom tabel, dalam poin. |
| rowHeights | double[] | Array double yang mewakili tinggi baris tabel, dalam poin. |

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) yang baru dibuat.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Membuat tabel baru dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat tabel akan dimasukkan. |
| x | float | Koordinat x tabel, dalam poin. |
| y | float | Koordinat y tabel, dalam poin. |
| columnWidths | double[] | Array double yang mewakili lebar kolom tabel, dalam poin. |
| rowHeights | double[] | Array double yang mewakili tinggi baris tabel, dalam poin. |

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) yang baru dibuat.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus shape pada indeks yang ditentukan dari koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol shape yang akan dihapus. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Menghapus kemunculan pertama shape yang ditentukan dari koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua shape dari koleksi shape.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan diklon. |
| x | float | Koordinat x bingkai shape yang diklon, dalam poin. |
| y | float | Koordinat y bingkai shape yang diklon, dalam poin. |
| width | float | Lebar bingkai shape yang diklon, dalam poin. |
| height | float | Tinggi bingkai shape yang diklon, dalam poin. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. Shape baru mempertahankan lebar dan tinggi sourceShape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan diklon. |
| x | float | Koordinat x bingkai shape yang diklon, dalam poin. |
| y | float | Koordinat y bingkai shape yang diklon, dalam poin. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. Shape yang diklon mempertahankan posisi dan ukuran aslinya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan diklon. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Membuat salinan shape yang ditentukan dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat shape yang diklon akan dimasukkan. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan diklon. |
| x | float | Koordinat x bingkai shape yang diklon, dalam poin. |
| y | float | Koordinat y bingkai shape yang diklon, dalam poin. |
| width | float | Lebar bingkai shape yang diklon, dalam poin. |
| height | float | Tinggi bingkai shape yang diklon, dalam poin. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Membuat salinan shape yang ditentukan dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. Shape baru mempertahankan lebar dan tinggi sourceShape.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat shape yang diklon akan dimasukkan. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan diklon. |
| x | float | Koordinat x bingkai shape yang diklon, dalam poin. |
| y | float | Koordinat y bingkai shape yang diklon, dalam poin. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Membuat salinan shape yang ditentukan dan memasukkannya ke dalam koleksi shape pada indeks yang ditentukan. Shape yang diklon mempertahankan posisi dan ukuran aslinya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat shape yang diklon akan dimasukkan. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) yang akan diklon. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) yang baru dibuat.