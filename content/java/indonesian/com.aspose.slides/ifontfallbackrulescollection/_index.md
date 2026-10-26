---
title: IFontFallBackRulesCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan aturan FontFallBack yang didefinisikan oleh pengguna
type: docs
url: /id/com.aspose.slides/ifontfallbackrulescollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Mewakili kumpulan aturan FontFallBack, yang didefinisikan oleh pengguna
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan aturan pada indeks yang ditentukan. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Menambahkan aturan FallBack baru ke akhir koleksi. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Menghapus kejadian pertama dari aturan FallBack tertentu dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


Mendapatkan aturan pada indeks yang ditentukan. Hanya-baca [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Mengambil koleksi aturan yang kosong atau telah diinisialisasi dari FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Menambahkan beberapa aturan ke dalam koleksi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Mengambil objek aturan pertama dalam koleksi
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


Menambahkan aturan FallBack baru ke akhir koleksi.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Mengambil koleksi aturan yang kosong atau telah diinisialisasi dari FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Menambahkan aturan baru ke dalam koleksi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Aturan yang ditentukan untuk ditambahkan |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


Menghapus kejadian pertama dari aturan FallBack tertentu dari koleksi.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Mengambil koleksi aturan yang kosong atau telah diinisialisasi dari FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Menambahkan beberapa aturan ke dalam koleksi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Mengambil objek aturan pertama dalam koleksi
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Menghapus 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Aturan yang akan dihapus dari koleksi. |