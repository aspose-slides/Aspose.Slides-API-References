---
title: Details_FileNotFoundException
second_title: Aspose.Slides for C++ API Reference
description: "The exception that is thrown when an attempt to access a file that does not exist on disk fails. Never create instances of this class manually. Use the FileNotFoundException class instead. Never wrap the FileNotFoundException class instances into System::SmartPtr."
type: docs
weight: 170
url: /cpp/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException class


The exception that is thrown when an attempt to access a file that does not exist on disk fails. Never create instances of this class manually. Use the FileNotFoundException class instead. Never wrap the FileNotFoundException class instances into [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Methods

| Method | Description |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Gets the name of the file that causes this exception. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |
## See Also

* Class [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)
