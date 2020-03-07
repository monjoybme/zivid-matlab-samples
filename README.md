# matlab-samples

This repository contains **MATLAB** code samples for **Zivid**.

## Samples list

There are two main categories of samples: **Camera** and **Applications**. The samples in the **Camera** category focus only on how to use the camera. The samples in the **Applications** category use the output generated by the camera, such as the 3D point cloud, a 2D image or other data from the camera. These samples shows how the data from the camera can be used.

- **Applications**
  - **Basic**
    - **FileFormats**
      - [**zdfread**][zdfread-url] - This examples shows how to read a Zivid point cloud from a .zdf file.
      - [**ReadIterateZDF**][ReadIterateZDF-url] - This example shows how to import and display a Zivid point cloud. In addition it shows how to iterate through, and extract individual points.
      - [**convertzdf**][convertzdf-url] - This example shows how to convert from .zdf to your preferred format (.ply, .csv, .txt, .png, .jpg, .bmp, .tiff).
  - **Advanced**
    - [**Downsample**][Downsample-url]  - This example shows how to import a Zivid point cloud and downsample it.

Note: The sample scripts require [**Image Processing Toolbox**](https://se.mathworks.com/products/image.html) and [**Computer Vision Toolbox**](https://se.mathworks.com/products/computer-vision.html).

## Instructions

1. [**Install Zivid Software**](https://www.zivid.com/downloads).
Note: The version tested with Zivid cameras is 1.8.0.

2. [**Install MATLAB Software**](https://se.mathworks.com/products/matlab.html).
Note: The version tested with Zivid cameras is 2019a.

3. Launch MATLAB.

4. Open and run one of the samples.

## Support
If you need assistance with using Zivid cameras, visit our Knowledge Base at [https://help.zivid.com/](https://help.zivid.com/) or contact us at [customersuccess@zivid.com](mailto:customersuccess@zivid.com).

## Licence
Zivid Samples are distributed under the [BSD license](https://github.com/zivid/matlab-samples/blob/master/LICENSE).

[Downsample-url]: source/Applications/Advanced/Downsample.m
[ReadIterateZDF-url]: source/Applications/Basic/FileFormats/ReadIterateZDF.m
[convertzdf-url]: source/Applications/Basic/FileFormats/convertzdf.m
[zdfread-url]: source/Applications/Basic/FileFormats/zdfread.m
