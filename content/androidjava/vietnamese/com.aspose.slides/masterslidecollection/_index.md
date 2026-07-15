---
title: MasterSlideCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một tập hợp các slide mẫu.
type: docs
url: /vi/com.aspose.slides/masterslidecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Biểu diễn một tập hợp các slide mẫu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số lượng phần tử thực tế có trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ số được chỉ định. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ số được chỉ định của bộ sưu tập. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Xóa các slide mẫu không sử dụng. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Thêm một bản sao của slide mẫu được chỉ định vào cuối bộ sưu tập. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Chèn một bản sao của slide mẫu được chỉ định vào vị trí chỉ định của bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một đối tượng đồng bộ gốc. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ bộ sưu tập. |
### size() {#size--}
```
public final int size()
```


Lấy số lượng phần tử thực tế có trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


Lấy phần tử tại chỉ số được chỉ định. Chỉ đọc [MasterSlide](../../com.aspose.slides/masterslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide mẫu cần xóa khỏi bộ sưu tập. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa phần tử tại chỉ số được chỉ định của bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số bắt đầu từ 0 của phần tử cần xóa.

--------------------

Để tránh ném PptxEditException, hãy kiểm tra thuộc tính HasDependingSlides của master trước. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


Xóa các slide mẫu không sử dụng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| ignorePreserveField | boolean | Xác định xem phương thức này có nên xóa master không sử dụng ngay cả khi thuộc tính [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) của nó được đặt là true hay không. |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


Thêm một bản sao của slide mẫu được chỉ định vào cuối bộ sưu tập. Các slide bố cục liên kết cũng sẽ được sao chép.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide để sao chép. |

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide đã thêm.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Chèn một bản sao của slide mẫu được chỉ định vào vị trí chỉ định của bộ sưu tập. Các slide bố cục liên kết cũng sẽ được sao chép.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Khởi tạo lớp Presentation để tải tệp bản trình bày nguồn
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Khởi tạo lớp Presentation cho bản trình bày đích (nơi slide sẽ được sao chép)
>      Presentation destPres = new Presentation();
>      try {
>          // Khởi tạo ISlide từ tập hợp các slide trong bản trình bày nguồn cùng với
>          // Slide master
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Lấy các Slide master của bản trình bày đích
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Sao chép slide master mong muốn từ bản trình bày nguồn vào tập hợp các master trong
>          // Bản trình bày đích
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Tập hợp các slide trong bản trình bày đích
>          ISlideCollection slds = destPres.getSlides();
>          // Sao chép slide nguồn vào tập hợp slide đích.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Lưu bản trình bày đích vào đĩa
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của slide mới. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide để sao chép. |

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide master đã chèn.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ số bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một đối tượng đồng bộ gốc. Chỉ đọc Object.

**Trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```


Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```


Trả về một iterator java cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Một java.util.Iterator cho toàn bộ bộ sưu tập.