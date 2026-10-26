---
title: AddPath()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan jalur yang ditentukan ke jalur yang diwakili oleh objek saat ini.
type: docs
weight: 222
url: /id/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) metode

Menambahkan jalur yang ditentukan ke jalur yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | Jalur yang akan ditambahkan |
| connect | **bool** | True menentukan bahwa figur pertama terakhir dalam **path** merupakan bagian dari figur terakhir pada jalur yang diwakili oleh objek saat ini; false menentukan bahwa figur pertama dalam **path** dan figur terakhir pada jalur yang diwakili oleh objek saat ini adalah figur yang terpisah |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Perpustakaan [Aspose.Slides](../../../)