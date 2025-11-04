# powershell_vs_python
Power shell vs python

See for yourself, PowerShell vs Python Benchmarking

In this example, I use PowerShell + C# script vs. Python.

Note: PowerShell scripts can run on Windows and Linux machines with the appropriate installations. With PowerShell, it's possible to create dynamic scripts similar to Python.

Windows 10 and 11 also work with PowerShell + C#, but only if the script is compatible with PowerShell 5.1.

It is also possible to run PowerShell + C# with a Dockerfile as long as you use the image: FROM mcr.microsoft.com/dotnet/sdk:8.0

# check performance
<a target="_blank" href="https://colab.research.google.com/github/zoreu/powershell_vs_python/blob/main/powershellvspython.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Preliminary Tests

```bash
# ----- sum of 100 million numbers ---

# powershell +C# script - sum of 100 million numbers
Result: 4999999950000000
Total time: 0.253 seconds

# python script - sum of 100 million numbers
Result: 4999999950000000
Total time: 6.320 seconds

# ----- sum of 1 billion numbers ---
# powershell +C# script - sum of 1 billion numbers
Result: 499999999500000000
Total time: 2.524 seconds

# python script - sum of 1 billion numbers
Result: 499999999500000000
Total time: 63.935 seconds
```


