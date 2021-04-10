#How to make custom pcbs for Fritzing using Inkscape. 

##### Needing to make a fairly simple 2 sided pcbs that was not a standard square or circle variant used in Fritzing I found any info very lacking on the web. Here I hope to show you how to accomplish that fairly painlessly. There are  a few examples on how to do but they're old and vague. I hope for the average user this guide will attempt to make it as painless as possible as to show the basics of designing a custom pcb. I will be using Inkscape on a Mac but it should very similar on other os's.

You can download this repository for the .svg file used in this how-to.

You can download Inkscape here: [![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Inkscape_Logo.svg/64px-Inkscape_Logo.svg.png)](https://inkscape.org/en/download/)

## Step 1.
1.1

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/1.1.png)

Fire up Inkscape and create a new file with **no_boarders**. 

---
1.2

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/1.2.png)

Open **Document Properties...**

---
1.3

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/1.3.png)

1. Change **Default units** to millimeters.
2. Change **Units** to millimeters.

---
1.4

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/1.4.png)

1. Select **Grids** tab and click **New**.

---
1.5

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/1.5.png)

1. Select **Grid**.
2. Change **Grid Units** to millimeters.
3. Choose a **Spacing X**.
4. Choose a **Spacing Y**.

## Step 2.
2.1

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/2.1.png)

1. Open **Layers...** up.

---
2.2

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/2.2.png)

1. Rename this layer to "board".

---
2.3

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/2.3.png)

1. Add a new layer.
2. Name it "silkscreen".
3. Select **Below Current**.
4. Click **Add**.

---
2.4

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/2.4.png)

1. Add a new layer.
2. Name it "silkscreen0".
3. Select **Below Current**.
4. Click **Add**.

---
2.5

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/2.5.png)

Now you have three layers. Board layer is the pcb. Silkscreen is the top silkscreen layer and silkscreen0 is the bottom silkscreen layer.

## Step 3.

3.1

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/3.1.png)

1. Select "board" layer.
2. Select "Star" tool.
3. Use either one.
4. Select number of corners.
5. Draw pcb shape.

---
3.2

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/3.2.png)

1. Set "width" to something reasonable.
2. Set "height" to something reasonable.

---
3.3

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/3.3.png)

1. Select shape.
2. Double click **Fill**.
3. Select flat color.
4. Change color to what you want, light colors work best.

---
3.4

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/3.4.png)

1. Select **Stroke paint**.
2. Make no paint.

---
3.5

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/3.5.png)

1. Select **Duplicate**.

---
3.6

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/3.6.png)

1. Select "Layer" and **Move Selection to Layer Below**.

---
3.7

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/3.7.png)

1. Select "silkscreen" layer.
2. Select **Duplicate**.

---
3.8

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/3.8.png)

1. Select "Layer" and **Move Selection to Layer Below**.

## Step 4.
4.1

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/4.1.png)

1. Lock "board" layer.
2. Unlock "silkscreen" layer.
3. Lock "silkscreen0" layer.
4. Select graphic.
5. Select **Fill** "no paint".

---
4.2

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/4.2.png)

1. Select **Stroke paint**.
2. Set **RGBA** to "ffffffff".

---
4.3

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/4.3.png)

1. Select **Stroke style**.
2. Set **Width** to "0.1" mm.

---
4.4

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/4.4.png)

1. Lock "board" layer.
2. Lock "silkscreen" layer.
3. Unlock "silkscreen0" layer.
4. Select graphic.
5. Select **Fill** "no paint".

---
4.5

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/4.5.png)

1. Select **Stroke paint**.
2. Select flat color.
3. Set **RGBA** to "ffffffff".

---
4.6

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/4.6.png)

1. Select **Stroke style**.
2. Set **Width** to "0.1" mm.

## Step 5.
5.1

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/5.1.png)

1. Select **XML Editor...**.

---
5.2

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/5.2.png)

1. Select "silkscreen0" layer.
2. Select "id" **Attribute**.
3. Change "id" **Value** to "silkscreen0".
4. Click **Set**.

---
5.3

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/5.3.png)

1. Select "silkscreen" layer.
2. Select "id" **Attribute**.
3. Change "id" **Value** to "silkscreen".
4. Click **Set**.

---
5.4

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/5.4.png)

1. Select "board" layer.
2. Select "id" **Attribute**.
3. Change "id" **Value** to "board".
4. Click **Set**.

## Add drill holes 
- Add holes to board layer
- Select pcb and one hole-> go to path and Difference
- Do this for all holes

## Step 6.
6.1

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/6.1.png)

1. Select **Document Properties...**.

---
6.2

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/6.2.png)

1. Select "page" tab.
2. Select **Resize to content...**.
3. Click  **Resize page to drawing or selection**.

## Step 7.
7.1

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/7.1.png)

1. Select **Save As...**.

---
7.2

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/7.2.png)

1. Select **Plain SVG**.

## Step 8.
8.1

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/8.1.png)

1. Open Fritzing to PCB tab, select the pcb and click **load image file**.

---
8.2

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/8.2.png)

1. Select .svg file we just made and click **Open**.

---
8.3

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/8.3.png)

Click **OK**. 

---
8.4

![](https://github.com/duff2013/Fritzing-Custom-PCB-HowTo/blob/master/img/8.4.png)

Now we see the pcb we just created!
