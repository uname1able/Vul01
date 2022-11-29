
#  <center> Vulnerability description
<center> There is a zipslip vul in MindMaster when open MindMaster project file ***.emmx

#  <center> Software version

<center><font color=blue size="3">Ver 10.0.8（2022.11.26update）</font></center>
<div aligen='center'><img src="./Image/Software_version.JPG"></div>


# <center> Software web
<center><font color=blue size="3">https://www.edrawsoft.cn/download/?type=1&tab=2</font></center>



# <center> Software Download link
<center><font color=blue size="3">https://cc-download.edrawsoft.cn/origin/mindmaster_cn_full5375.exe?_gl=1*16kqd32*_ga*MTU0ODQ4MzQuMTY2NzU0MzI5MA..*_ga_24WTSJBD5B*MTY2OTcyNzIxMS4yLjEuMTY2OTcyNzI2Ni41LjAuMA..</font></center>



# <center> Recurrennt enviorment
<center><font color=blue size="6">Win10</font></center>
<center><font color=blue size="6">MindMaster Ver 10.0.8 </font></center>

# <center> Recurrennt

<center> 1.Open project file **.emmx with WinHex. File Head is Zip format.
<center> <br>

<div aligen='center'><img src="./Image/WinHex.JPG"></div>
<center> <br>

<center> 2.So,Rename **.emmx to **.zip . Add ../../../../../../../../../../../../../../../../../poc.dll  file into **.zip file use python code 

<div aligen='center'><img src="./Image/Craft_zipfile.JPG"></div>
<center> <br>


<center> 3.Rename **.zip(Crafted) to **.emmx 
<center> <br>
<div aligen='center'><img src="./Image/Final_exp_projectfile.JPG"></div>
<center> <br>

<center> 5.MindMaster need Administrator permissions to release file to c:\ 
<center> <br>
<div aligen='center'><img src="./Image/Need_administrator_permissions.JPG"></div>
<center> <br>

<center> 6.Open project_fie.emmx and Open c:\ 
<center> <br>
<div aligen='center'><img src="./Image/exp.JPG"></div>
<center> <br>

<center> 7.Recurrent Sucessed!

