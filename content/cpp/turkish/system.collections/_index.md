---
title: "System::Collections"
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 300
url: /tr/system.collections/
---
## Sınıflar

| Class | Açıklama |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) indeksle erişilebilen bitler. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneği asla yığına (stack) ya da operator new kullanılarak oluşturulmamalıdır, aksi takdirde çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıf her zaman [System::SmartPtr](../system/smartptr/) göstericisine sarılmalı ve bu gösterici fonksiyonlara argüman olarak geçirilmelidir. |
| [BitArrayPtr](./bitarrayptr/) | [BitArray](./bitarray/)'a gösterici. Bu tip, diğer nesnenin silinmesini yönetmek için bir göstericidir. Yığına tahsis edilmeli ve fonksiyonlara değer veya const referans olarak geçirilebilmelidir. |
| [CollectionBase](./collectionbase/) | Güçlü tiplenmiş bir koleksiyon için soyut bir temel sınıf sağlar. |
| [ICollection](./icollection/) | Generic olmayan koleksiyon arayüzünü tanımlar. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) yineleme yapılabilen tüm generic olmayan koleksiyonlar için temel arayüzdür. |
| [IEnumerator](./ienumerator/) | Belirli öğeler arasında yineleme yapmak için kullanılabilen enumerator arayüzü. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneği asla yığına ya da operator new kullanılarak oluşturulmamalıdır, aksi takdirde çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıf her zaman [System::SmartPtr](../system/smartptr/) göstericisine sarılmalı ve bu gösterici fonksiyonlara argüman olarak geçirilmelidir. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Genel Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) üzerine generic olmayan [IEnumerator](./ienumerator/) uygulaması oluşturan sarmalayıcı - Referans Tipleri için sarmalayıcı. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Genel Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) üzerine generic olmayan [IEnumerator](./ienumerator/) uygulaması oluşturan sarmalayıcı - Değer Tipleri için sarmalayıcı. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) indeksle bireysel olarak erişilebilen nesnelerden oluşan generic olmayan bir koleksiyonu temsil eder. |
| [IListImplRefType](./ilistimplreftype/) | Referans tipleri için [System::Collections::Generic::List](../system.collections.generic/list/) nesnesi üzerinde [System::Collections::IList](./ilist/) arayüzünü uygulayan Stub. |
| [IListImplValueType](./ilistimplvaluetype/) | Değer tipleri için [System::Collections::Generic::List](../system.collections.generic/list/) nesnesi üzerinde [System::Collections::IList](./ilist/) arayüzünü uygulayan Stub. |
| [IListWrapper](./ilistwrapper/) | Generic'den generic olmayan koleksiyona dönüştürmeyi destekleyen arayüz. |
| [Invalidatable](./invalidatable/) | [InvalidatableTracker](./invalidatabletracker/) nesneleri aracılığıyla alt sınıflarının durumunu izlemeyi mümkün kılan sınıf. |
| [InvalidatableTracker](./invalidatabletracker/) | [Invalidatable](./invalidatable/) nesnelerinin izleyicilerini uygulayan sınıf. |