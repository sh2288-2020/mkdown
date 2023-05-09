\# mkdown
md语法学习

`md学习`

```powershell
$n = 999
while ($n -ne 100) {
    $444 = ""
    $111 = Get-Clipboard
    $22 = $111.split([System.Environment]::NewLine, [System.StringSplitOptions]::RemoveEmptyEntries)
    foreach ($i in $22) {
        $222 = $i.split("`t")
        $333 = $222[6], $222[4], $222[5], $222[1], "CHNXX005", "YES", [System.Environment]::NewLine -Join "`t"
        $444 += $333
    }
    Set-Clipboard $444
    write-output $444+" all result had been send to clipboard"
    pause
    $n -= 1
}
```
---
这是一个链接 ![Markdown语法](https://markdown.com.cn/assets/img/philly-magic-garden.9c0b4415.jpg)

```c#
using System;
using System.Drawing;
using System.Windows.Forms;
namespace png2clip2
{
	class Program
	{
		[STAThread]
		private static void Main(string[] args)
		{
			if (args.Length != 0) {
				Image img = Image.FromFile(args[0]);
				Clipboard.SetImage(img);
			}
		}
	}
}
```


| Syntax      | Description | 列3
| ----------- | ----------- | --
| Header      | Title       | 33
| Paragraph   | Text        | 33
