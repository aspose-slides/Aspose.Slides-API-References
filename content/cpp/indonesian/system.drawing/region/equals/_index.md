---
title: Equals()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah region yang ditentukan identik dengan region yang diwakili oleh objek saat ini pada permukaan gambar yang ditentukan.
type: docs
weight: 157
url: /id/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) method


Menentukan apakah region yang ditentukan identik dengan region yang diwakili oleh objek saat ini pada permukaan gambar yang ditentukan.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Region yang akan dibandingkan dengan region ini |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Permukaan gambar |

### Nilai Kembalian

Benar jika interior dari region yang ditentukan identik dengan interior dari region yang diwakili oleh objek saat ini ketika transformasi yang terkait dengan parameter **g** diterapkan; selain itu - salah

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Region](../)
* Kelas [Graphics](../../graphics/)
* Ruang Nama [System::Drawing](../../)
* Library [Aspose.Slides](../../../)