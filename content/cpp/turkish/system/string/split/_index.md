---
title: Split()
second_title: Aspose.Slides için C++ API Referansı
description: Diziyi karaktere göre böler.
type: docs
weight: 768
url: /tr/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const metodu

Diziyi karaktere göre böler.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | char_t | Dizeyi bölmek için kullanılan karakter. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Bölme seçenekleri. |

### Dönüş Değeri

[Array](../../array/) alt dizi.

## String::Split(char_t, int32_t, StringSplitOptions) const metodu

Diziyi karaktere göre böler.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | char_t | Dizeyi bölmek için kullanılan karakter. |
| count | **int32_t** | Döndürülecek alt dizilerin maksimum sayısı. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Bölme seçenekleri. |

### Dönüş Değeri

[Array](../../array/) alt dizi.

## String::Split(char_t, char_t, StringSplitOptions) const metodu

Diziyi iki karakterden birine göre böler.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separatorA | char_t | Bölme için kullanılan ilk karakter. |
| separatorB | char_t | Bölme için kullanılan ikinci karakter. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Bölme seçenekleri. |

### Dönüş Değeri

[Array](../../array/) alt dizi.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const metodu

Diziyi belirtilen karakterlerden biriyle böler.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ayırıcı karakterler. Boş ise, herhangi bir boşluk karakteri ayırıcı olarak kabul edilir. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Bölme seçenekleri. |

### Dönüş Değeri

[Array](../../array/) alt dizi.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const metodu

Diziyi belirtilen karakterlerden biriyle böler.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ayırıcı karakterler. Boş ise, herhangi bir boşluk karakteri ayırıcı olarak kabul edilir. |
| count | **int32_t** | Döndürülecek alt dizilerin maksimum sayısı. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Bölme seçenekleri. |

### Dönüş Değeri

[Array](../../array/) alt dizi.

## String::Split(const String\&, StringSplitOptions) const metodu

Diziyi alt dizeye göre böler.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | const [String](../)\& | Ayırıcı görevi gören alt dize. Boş ise, boşluk karakteri ayırıcı olarak davranır. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Bölme seçenekleri. |

### Dönüş Değeri

[Array](../../array/) alt dizi.

## String::Split(const String\&, int, StringSplitOptions) const metodu

Diziyi alt dizeye göre böler.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | const [String](../)\& | Ayırıcı görevi gören alt dize. Boş ise, boşluk karakteri ayırıcı olarak davranır. |
| count | int | Bölümler dizisindeki öğelerin maksimum sayısı. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Bölme seçenekleri. |

### Dönüş Değeri

[Array](../../array/) alt dizi.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const metodu

Diziyi alt dizeye göre böler.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) ayırıcı dizeler. Boş ise, bölme yapılmaz. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Bölme seçenekleri. |

### Dönüş Değeri

[Array](../../array/) alt dizi.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const metodu

Diziyi alt dizeye göre böler. Şu anda yalnızca sıfır veya bir elemanlı ayırıcı dizilerini destekler.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) ayırıcı dizeler. Boş ise, bölme yapılmaz. |
| count | int | Bölümler dizisindeki öğelerin maksimum sayısı. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Bölme seçenekleri. |

### Dönüş Değeri

[Array](../../array/) alt dizi.

## İlgili

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)