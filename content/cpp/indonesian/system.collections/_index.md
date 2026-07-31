---
title: "System::Collections"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 300
url: /id/system.collections/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) dari bit yang dapat diakses dengan indeks. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan assert. Selalu bungkus kelas ini ke dalam penunjuk [System::SmartPtr](../system/smartptr/) dan gunakan penunjuk tersebut untuk meneruskannya ke fungsi sebagai argumen. |
| [BitArrayPtr](./bitarrayptr/) | Penunjuk ke [BitArray](./bitarray/). Tipe ini adalah penunjuk untuk mengelola penghapusan objek lain. Ini harus dialokasikan pada stack dan diteruskan ke fungsi baik dengan nilai maupun dengan referensi konstanta. |
| [CollectionBase](./collectionbase/) | Menyediakan kelas dasar abstrak untuk koleksi yang kuat tipe. |
| [ICollection](./icollection/) | Mendefinisikan antarmuka koleksi non-generic. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) adalah antarmuka dasar untuk semua koleksi non-generic yang dapat diiterasi. |
| [IEnumerator](./ienumerator/) | Antarmuka enumerator yang dapat digunakan untuk mengiterasi beberapa elemen. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan assert. Selalu bungkus kelas ini ke dalam penunjuk [System::SmartPtr](../system/smartptr/) dan gunakan penunjuk tersebut untuk meneruskannya ke fungsi sebagai argumen. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Pembungkus yang membuat implementasi non-generic [IEnumerator](./ienumerator/) di atas Iterator generic [IEnumeratorImplRefType](./ienumeratorimplreftype/) - pembungkus untuk Tipe Referensi. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Pembungkus yang membuat implementasi non-generic [IEnumerator](./ienumerator/) di atas Iterator generic [IEnumeratorImplRefType](./ienumeratorimplreftype/) - pembungkus untuk Tipe Nilai. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Mewakili koleksi non-generic dari objek yang dapat diakses secara individual dengan indeks. |
| [IListImplRefType](./ilistimplreftype/) | Stub yang mengimplementasikan antarmuka [System::Collections::IList](./ilist/) pada objek [System::Collections::Generic::List](../system.collections.generic/list/). Implementasi untuk tipe referensi. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub yang mengimplementasikan antarmuka [System::Collections::IList](./ilist/) pada objek [System::Collections::Generic::List](../system.collections.generic/list/). Implementasi untuk tipe nilai. |
| [IListWrapper](./ilistwrapper/) | Antarmuka untuk mendukung casting dari koleksi generic ke non-generic. |
| [Invalidatable](./invalidatable/) | Kelas yang memungkinkan pelacakan status keturunannya melalui objek [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | Kelas yang mengimplementasikan pelacak objek [Invalidatable](./invalidatable/). |