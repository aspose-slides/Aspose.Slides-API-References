---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides برای C++ مرجع API
description: 
type: docs
weight: 963
url: /fa/system.testpredicates.typetraits/
---
## ساختارها

| ساختار | توضیح |
| --- | --- |
| [has_data_method](./has_data_method/) | بررسی می‌کند آیا یک نوع متد data() دارد. اگر داشته باشد، std::true_type را ارث می‌برد، در غیر این صورت std::false_type را ارث می‌برد. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | تخصص برای نوع BitArray که نوع boost را فراهم می‌کند که در آن دسترس‌پذیر نیست. |
| [has_print_to_method](./has_print_to_method/) | بررسی می‌کند آیا تابع PrintTo برای نوع داده‌شده به عنوان آرگومان اول overload دارد. اگر overload وجود داشته باشد، std::true_type را ارث می‌برد، در غیر این صورت std::false_type را ارث می‌برد. |
| [IsCppContainer](./iscppcontainer/) | بررسی می‌کند آیا نوع مشخص، یک container سبک STL است. برای این کار، وجود انواع عضو iterator و const_iterator را بررسی می‌کند. اگر هر دو وجود داشته باشند، std::true_type را ارث می‌برد، در غیر این صورت std::false_type را ارث می‌برد. |
| [IsEnumerable](./isenumerable/) | بررسی می‌کند آیا نوع، تخصص [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) را به عنوان پایه دارد. اگر چنین باشد، مقدار عضو به true تنظیم می‌شود، در غیر این صورت به false تنظیم می‌شود. |
| [LargestFPType](./largestfptype/) | یک نام مستعار برای طولانی‌ترین نوع عدد شناور فراهم می‌کند. انواع غیر عدد شناور را نادیده می‌گیرد. |

## تعاریف نوع

| تایپ‌دِف | توضیح |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | بررسی می‌کند که **T1** عددی (arithmetic) باشد و **T2** عدد شناور (floating point) یا بالعکس. اگر چنین باشد، مقدار عضو به true تنظیم می‌شود، در غیر این صورت false است. |
| [AnyOfDecimal](./anyofdecimal/) | بررسی می‌کند که حداقل یکی از آرگومان‌های نوع [System::Decimal](../system/decimal/) باشد. اگر چنین باشد، مقدار عضو به true تنظیم می‌شود، در غیر این صورت false است. |
| [IsArray](./isarray/) | بررسی می‌کند آیا نوع، یک تخصص [System::Array](../system/array/) است. اگر چنین باشد، مقدار عضو به true تنظیم می‌شود، در غیر این صورت به false تنظیم می‌شود. |
| [IsList](./islist/) | بررسی می‌کند آیا نوع، یک تخصص [System::Collections::Generic::List](../system.collections.generic/list/) است. اگر چنین باشد، مقدار عضو به true تنظیم می‌شود، در غیر این صورت به false تنظیم می‌شود. |
| [BothArrayOrList](./botharrayorlist/) | بررسی می‌کند آیا هر دو آرگومان نوع، آرایه یا لیست هستند. اگر چنین باشد، مقدار عضو به true تنظیم می‌شود، در غیر این صورت به false تنظیم می‌شود. |
| [BothEnumerable](./bothenumerable/) | بررسی می‌کند آیا هر دو آرگومان نوع، IEnumerable هستند. اگر چنین باشد، مقدار عضو به true تنظیم می‌شود، در غیر این صورت به false تنظیم می‌شود. |