---
page_type: sample
languages:
- csharp
- cpp
- cppwinrt
products:
- windows
- windows-uwp
urlFragment: PowerGrid
extendedZipContent:
- path: SharedContent
  target: SharedContent
- path: LICENSE
  target: LICENSE
description: "Shows how to use power grid forecasts."
---

# Power grid forecast sample

> **Note:** This sample is part of a large collection of UWP feature samples. 
> You can download this sample as a standalone ZIP file
> [from docs.microsoft.com](https://docs.microsoft.com/samples/microsoft/windows-universal-samples/resizeappview/),
> or you can download the entire collection as a single
> [ZIP file](https://github.com/Microsoft/Windows-universal-samples/archive/master.zip), but be 
> sure to unzip everything to access shared dependencies. For more info on working with the ZIP file, 
> the samples collection, and GitHub, see [Get the UWP samples from GitHub](https://aka.ms/ovu2uq). 
> For more samples, see the [Samples portal](https://aka.ms/winsamples) on the Windows Dev Center. 

Shows how to use the PowerGrid Forecast API.

This sample covers the following:
- Obtaining the power grid forecast
- Registering for ForecastUpdated notifications
- Looking for the lowest severity in a specified timeframe

**Note** The Windows universal samples require Visual Studio to build and Windows 11 to execute.
 
To obtain information about Windows development, go to the [Windows Dev Center](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio and the tools for developing Windows apps, go to [Visual Studio](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Reference

[PowerGridForecast class](https://learn.microsoft.com/uwp/api/windows.devices.power.powergridforecast)

### Related samples

[Power grid forecast from a Win32 app](https://github.com/microsoft/Windows-classic-samples/tree/main/Samples/PowerGrid)

## System requirements

- Windows 11 SDK (build 26100 or higher)
- Windows 11 (build 26100 or higher)

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or select Debug > Start Without Debugging. 

