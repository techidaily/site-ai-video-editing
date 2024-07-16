---
title: New Blender Green Screen Effects
date: 2024-05-19T05:12:12.572Z
updated: 2024-05-20T05:12:12.572Z
tags: 
  - ai
  - animation videos
categories: 
  - ai
description: This Article Describes New Blender Green Screen Effects
excerpt: This Article Describes New Blender Green Screen Effects
keywords: ai animation blender green screen effects,green screen after effects,how to create a green screen video in after effects,how to use blender green screen,blender green screen effects,ai animation how to use blender green screen,blender green screen
thumbnail: https://www.lifewire.com/thmb/WSLZcqxwmXkq850tQOgpRjODDjE=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/football-referee-signaling-touchdown-in-stadium-599944339-5a84cb9e875db900367df025.jpg
---

## Blender Green Screen Effects

Blender is an open-source cross-platform 3D graphics program, but this doesn’t mean it’s a low-rent option. Just like commercial packages like Lightwave 3D, it is also a very capable compositing package. Unlike Lightwave, it is a modern node-based compositor like Nuke or Fusion. It’s not what the software is designed for, but it does a bangup job of green screen compositing, as you will soon see.

Blender green screen uses technique of the ****chroma key** a color is isolated (in our case the green of the****green screen**), or a particular luminance, it is removed and the area that was occupied by it becomes transparent, thus becoming part of the alpha channel. The transparent parts will thus show the video or the image below, which will thus define the environment in which the subject of the first movie will act.

## How to Use Green Screen in Blender

So we need to pull these two elements into Blender and pull a key on the green bits to make the background show through in as naturalistic a way as possible. Blender is a node-based compositor which means the control mechanism is nodes or little LEGO blocks of love which you place on the screen and link with little strings which form your signal path.

![blender](https://images.wondershare.com/filmora/article-images/blender-interface.jpg)

Locate the drop-down (it goes up, actually, but you know what we mean) at the bottom of the view, and select “Movie Clip Editor.”

Click the “Open” button and choose and load your green screen footage. (You can also load sequences of images for uncompressed keys in this step if you have the space, and the footage is the right size.)

Once the clip is loaded, go back to the drop-down and select Node Editor.

The screen will be blank, but just go to the bottom of the view and click the middle button marked “Node Tree Type” to Display, and then check the Use Nodes and Backdrop buttons.

Select the “Render Layers” node, and because we won’t need it you can delete it (on the Mac this is the Forward Delete key). Then move the Compositing node out of the way because we won’t need it yet.

****Note:** to zoom in and out of the nodes, use the centre scroll wheel of the mouse if you have it. To zoom in and out of the images you are working on, use the V and Alt-V keys.

****Compositing Nodes**

Click the Add menu in the bar at the bottom of the view and select “Input -> Movie Clip.” Select the green screen clip you added in the Movie Clip Editor. This is the input. We have to push this through a keyer to remove the green and make those areas transparent.

****Important:** in this program flow goes from left to right, so node inputs are on the left of a node, and outputs are on the right of a node.

Now select “Add -> Matte -> Keying” to add a keying node. Also “Add -> Output -> Viewer” to make the output from the key visible. Click on the little yellow dot next to Image output on the Input node, and drag it to Image input on the Keying node. Then drag the little dot next to Image output on the keying node, and drag it to the image input on the viewer node.

You now have to select the key colour, the colour which the keyer is changing to transparent. Click the Key Colour button on the Keying node, and this displays a colour selector. Click the eyedropper, and click on the image in the background somewhere on the green screen.

If you look carefully, you will see that there are some areas which still have a bit of colour and are not fully transparent. You can check this more accurately by dragging the string from the Matte output on the Keying node and linking to the input on the viewer. This is the key you have made. As you can see, the dark bits are supposed to be totally black, and there are still greys showing through. (This is because the source material wasn’t perfect.)

There are many different ways to fix this depending on the shot, but if it’s a reasonably well-shot green screen, all you will need to do is the following.

Adjust the Black Clip slider to expand the amount of greens which turn to black. Then adjust the White Clip to push the whites to prevent them from becoming transparent.

Once you have pure white and pure black, reconnect the image output of the keying node to the image input on the viewer, and you’ll see you have a decent key.

You can adjust the amount of fringing and spill (reflections from the green screen on the model), but generally the keyer does a good job of guessing that for you with a decently-shot green screen.

****Adding the background**

After this, adding the background is more of the same with a slight twist. “Add -> Input -> Movie Clip,” navigate to your background clip and load it.

To blend the two layers, you have to make a mix of the two clips so that the background shows through the now transparent bits of the foreground.

“Add -> Colour -> Mix node”. Take the output from the background clip, and feed it to the top image input of the mix node. Take the output from the keying node, and feed it into the lower image input on the mix node.

Click the Alpha channel button next to the drop-down on the mix node.

And finally we have our key. The background is way too sharp and makes the green screen footage look really soft and crappy, so we need to soften the background. There is a really nice Bokeh Blur filter in blender for just this purpose to make the background look out of focus and add lots of gorgeous Bokeh blobs.

“Add -> Filter -> Bokeh Blur” and put it between the background clip and the mix. In Blender, if you add a node and place it over a string between two nodes, the string goes yellow, and dropping it will automatically insert the new node into the signal path connecting inputs and outputs.

Finally add an image to the Bokeh Blur for the shape you want the bokeh to be; we opted for a donut-shaped iris pattern.

To render out your video, connect the output of the Mix node to the input of the compositing node we left lying about earlier. It’s okay for this output to be connected to the input node of the viewer, too, as this means we see progress while rendering.

Make sure you are set up to render the right amount of frames at 30fps in the render panel on the far right. 30fps for 5 seconds (the duration of our clip) is 150 frames. Insert 150 where it says End Fr.

Select a place and a filename to output to in the Output panel further down the right-hand side. Then to render, select the info menu bar from the top-left drop-down, and finally choose “Render Menu -> Render Animation,” and the render will begin.

## Wondershare Filmora

If you're just starting out with video editing, or just want a simple program that works, Wondershare Filmora might be what you're looking for. It has the essential tools, and anyone can learn to use it easily.

Wondershare Filmora is the one of best video editing software with cool features that compares to other competing video editing Softwares. Many video editing programs claim to offer professional results; Filmora is one of a few consumer-level tools that actually delivers.

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For Win 7 or later (64-bit)

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

**Installation Steps**

1. Click the icon in the center of the Media Library to add files directly.
2. Go File > Import Media > Import Media Files.
3. Drag and drop to the Media Library directly.

While importing a media file, Wondershar Filmora may ask you if you wish to create a proxy file to accelerate the editing process. Select "Yes" to have a fast video editing experience.

![drag green screen](https://images.wondershare.com/filmora/guide/drag-green-screen-video-win.jpg)

You can also import video clips using your Touch Bar controls if your computer has Touch Bar.

### Related FAQs

**How do I get rid of the green screen in blender?**

This is achieved by Compositing Nodes: Click the Add menu in the bar at the bottom of the view and select “Input -> Movie Clip.” Select the green screen clip you added in the Movie Clip Editor. This is the input. We have to push this through a keyer to remove the green and make those areas transparent.

**How do I get rid of objects in green screen?**

This can be done by following these prompts: Select “Add -> Matte -> Keying” to add a keying node. Also “Add -> Output -> Viewer” to make the output from the key visible. Click on the little yellow dot next to Image output on the Input node, and drag it to Image input on the Keying node. Then drag the little dot next to Image output on the keying node, and drag it to the image input on the viewer node.

## Conclusion

Obviously, to get the best green screen composites you have to shoot good “plates.” “Plates” are the main bits of the shot that you bolt together in movie visual effects. You have the foreground plate and the green screen bit with an actor filmed in front of a green screen. Then you have the background plate which is the bit you want to show through the green bits of the foreground, making the whole thing look as though the background and foreground were filmed at the same time.

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

**Installation Steps**

1. Click the icon in the center of the Media Library to add files directly.
2. Go File > Import Media > Import Media Files.
3. Drag and drop to the Media Library directly.

While importing a media file, Wondershar Filmora may ask you if you wish to create a proxy file to accelerate the editing process. Select "Yes" to have a fast video editing experience.

![drag green screen](https://images.wondershare.com/filmora/guide/drag-green-screen-video-win.jpg)

You can also import video clips using your Touch Bar controls if your computer has Touch Bar.

### Related FAQs

**How do I get rid of the green screen in blender?**

This is achieved by Compositing Nodes: Click the Add menu in the bar at the bottom of the view and select “Input -> Movie Clip.” Select the green screen clip you added in the Movie Clip Editor. This is the input. We have to push this through a keyer to remove the green and make those areas transparent.

**How do I get rid of objects in green screen?**

This can be done by following these prompts: Select “Add -> Matte -> Keying” to add a keying node. Also “Add -> Output -> Viewer” to make the output from the key visible. Click on the little yellow dot next to Image output on the Input node, and drag it to Image input on the Keying node. Then drag the little dot next to Image output on the keying node, and drag it to the image input on the viewer node.

## Conclusion

Obviously, to get the best green screen composites you have to shoot good “plates.” “Plates” are the main bits of the shot that you bolt together in movie visual effects. You have the foreground plate and the green screen bit with an actor filmed in front of a green screen. Then you have the background plate which is the bit you want to show through the green bits of the foreground, making the whole thing look as though the background and foreground were filmed at the same time.

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

**Installation Steps**

1. Click the icon in the center of the Media Library to add files directly.
2. Go File > Import Media > Import Media Files.
3. Drag and drop to the Media Library directly.

While importing a media file, Wondershar Filmora may ask you if you wish to create a proxy file to accelerate the editing process. Select "Yes" to have a fast video editing experience.

![drag green screen](https://images.wondershare.com/filmora/guide/drag-green-screen-video-win.jpg)

You can also import video clips using your Touch Bar controls if your computer has Touch Bar.

### Related FAQs

**How do I get rid of the green screen in blender?**

This is achieved by Compositing Nodes: Click the Add menu in the bar at the bottom of the view and select “Input -> Movie Clip.” Select the green screen clip you added in the Movie Clip Editor. This is the input. We have to push this through a keyer to remove the green and make those areas transparent.

**How do I get rid of objects in green screen?**

This can be done by following these prompts: Select “Add -> Matte -> Keying” to add a keying node. Also “Add -> Output -> Viewer” to make the output from the key visible. Click on the little yellow dot next to Image output on the Input node, and drag it to Image input on the Keying node. Then drag the little dot next to Image output on the keying node, and drag it to the image input on the viewer node.

## Conclusion

Obviously, to get the best green screen composites you have to shoot good “plates.” “Plates” are the main bits of the shot that you bolt together in movie visual effects. You have the foreground plate and the green screen bit with an actor filmed in front of a green screen. Then you have the background plate which is the bit you want to show through the green bits of the foreground, making the whole thing look as though the background and foreground were filmed at the same time.

[Try It Free](https://tools.techidaily.com/wondershare/filmora/download/)

For macOS 10.12 or later

**Installation Steps**

1. Click the icon in the center of the Media Library to add files directly.
2. Go File > Import Media > Import Media Files.
3. Drag and drop to the Media Library directly.

While importing a media file, Wondershar Filmora may ask you if you wish to create a proxy file to accelerate the editing process. Select "Yes" to have a fast video editing experience.

![drag green screen](https://images.wondershare.com/filmora/guide/drag-green-screen-video-win.jpg)

You can also import video clips using your Touch Bar controls if your computer has Touch Bar.

### Related FAQs

**How do I get rid of the green screen in blender?**

This is achieved by Compositing Nodes: Click the Add menu in the bar at the bottom of the view and select “Input -> Movie Clip.” Select the green screen clip you added in the Movie Clip Editor. This is the input. We have to push this through a keyer to remove the green and make those areas transparent.

**How do I get rid of objects in green screen?**

This can be done by following these prompts: Select “Add -> Matte -> Keying” to add a keying node. Also “Add -> Output -> Viewer” to make the output from the key visible. Click on the little yellow dot next to Image output on the Input node, and drag it to Image input on the Keying node. Then drag the little dot next to Image output on the keying node, and drag it to the image input on the viewer node.

## Conclusion

Obviously, to get the best green screen composites you have to shoot good “plates.” “Plates” are the main bits of the shot that you bolt together in movie visual effects. You have the foreground plate and the green screen bit with an actor filmed in front of a green screen. Then you have the background plate which is the bit you want to show through the green bits of the foreground, making the whole thing look as though the background and foreground were filmed at the same time.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

## Discover a Quick Guide to Add Personalized Video Filters in VN App. Learn How to Use Built-In Filters and Import External Ones for Creative Video Editing

In the colorful world of video editing, the ability to personalize and enhance your clips with unique looks is what stands your work out. Enter the VN app, the game-changer in mobile video editing, bursting with user-friendly features.

If you've been searching for a simple way to dive into the realm of video filters, you're in luck. Today, we'll decode how to jazz up your videos using the VN app's built-in and custom video filter features. Ready to elevate your video content game? Let's get started!

* [Step 2: Save the Filter Preset and Use It Directly Next Time](#part2)
* [Part 3: Best Alternatives](#part3)
* [Part 4: Summary](#part4)

## Part 1: Use VN App Built-in Video Filters (LUTs)

**_Step 1: Locate the Filters Feature_**

You must know where the magic happens before you go Spielberg on your videos. Upon launching the VN app, you'll see a range of editing tools. Look for an icon resembling a magic wand or palette – your gateway to the wonderful world of video filters.

**_Step 2: Preview and Apply Effects_**

This step is all about experimenting and having fun. Tap on the filter icon, and voilà! You're greeted with various preset looks, waiting for your videos to don them. Glide through the options; VN has got it all from vintage vibes to futuristic glow. Found one that catches your eye?

Tap on it and watch your video transform instantly. Not sure about your pick? No worries; simply swipe left or right to preview other effects. Once you're satisfied, tap 'apply.'

**_Step 3: Adjust Details with Color Settings_**

Okay, young director, you've chosen your filter. But what if you want to tweak it just a bit? VN's got your back.

Once a filter is applied, you'll notice sliders or dials – these are your video filter editor tools. Play around with them! You can adjust the filter's intensity, making it as subtle or dramatic as you like. Tweak the brightness, contrast, and saturation until your video looks like you envisioned.

## Part 2: Download External Filter Installation Package

**_Step 1: Locate the My Filters Feature_**

The VN app is awesome, but can you add even more flair to your videos with custom filters? Yup! These aren't just your regular video presets – they're unique styles you can download and add to your VN arsenal.

To begin, tap on the “My Filters” section within the app. If you're wondering where this is, it's usually nestled beside the built-in filter options, represented by a '+' or 'Add' icon. This personal space is ready to be filled with your downloaded filter goodies.

**_Step 2: Import the Downloaded VN Filter APK_**

Here comes the cool part! To get new custom filters:

1. Visit the website or store where the VN filters are available for download. (**Hint:** Search for “vn filter download APK" or "vn iPhone filter download” based on your device.)
2. Once downloaded, head back to the VN app and click the **'Add'** or '+' icon in the **“My Filters”**
3. Navigate to your device's download folder or wherever the vn filter apk is saved.
4. Select the filter file (it should have a .apk or similar extension for Android users and a different format for iPhone users).
5. Tap on **'Import'** and wait for the magic to happen. Your brand-new filter will now be housed in **“My Filters”**!

**_Step 2: Save the Filter Preset and Use It Directly Next Time_**

After importing your snazzy new filter, the next step is super easy. Simply apply it to your video, and if you love how it looks, save it as a preset. This way, the next time you're editing, you can head straight to **"My Filters**," find your favorite custom filter and slap it onto your video without a hitch. Talk about convenience!

## Part 3: Best Alternatives

Though VN offers many fantastic filter options, it's always nice to have alternatives, right? Meet Filmora, another stellar video editing tool known for its expansive video filter collection.

Filmora is more than just an editor; it's a canvas for videographers. One of its most raved-about features is its extensive range of video filters. With Filmora, you can transport your audience from a sun-kissed beach to a moody, rain-soaked alley in just a tap. Whether you’re going for a documentary feel, a Hollywood movie vibe, or something out of a dream, Filmora's filters have covered you.

**Getting started is a breeze:**

1. Launch Filmora and import your video.
2. Head to the **“Effects”** tab and immerse yourself in the filter options.
3. Preview, select, and apply – it’s that simple!
4. Like VN, Filmora allows you to tweak the filter settings for that perfect look.

While Filmora is a great tool, the best fit depends on personal preferences and specific project needs. However, it's always good to have choices in your editing toolkit. Variety is, after all, the spice of life (and video editing)!

## Part 4: Summary

The beauty of video editing lies in the limitless possibilities it offers. With every video filter, editor tweak, and custom preset, you're not just editing – you're storytelling. And with tools like VN and Filmora at your fingertips, you have everything you need to tell your story your way.

Remember, whether you're a seasoned videographer or someone just starting, there's no 'right' or 'wrong' regarding creativity. Play around, experiment, and, most importantly, have fun with the process. In the vast universe of video editing, every filter is a star waiting to shine on your masterpiece.

Part 1: Use VN App Built-in Video Filters (LUTs)

**_Step 1: Locate the Filters Feature_**

You must know where the magic happens before you go Spielberg on your videos. Upon launching the VN app, you'll see a range of editing tools. Look for an icon resembling a magic wand or palette – your gateway to the wonderful world of video filters.

**_Step 2: Preview and Apply Effects_**

This step is all about experimenting and having fun. Tap on the filter icon, and voilà! You're greeted with various preset looks, waiting for your videos to don them. Glide through the options; VN has got it all from vintage vibes to futuristic glow. Found one that catches your eye?

Tap on it and watch your video transform instantly. Not sure about your pick? No worries; simply swipe left or right to preview other effects. Once you're satisfied, tap 'apply.'

**_Step 3: Adjust Details with Color Settings_**

Okay, young director, you've chosen your filter. But what if you want to tweak it just a bit? VN's got your back.

Once a filter is applied, you'll notice sliders or dials – these are your video filter editor tools. Play around with them! You can adjust the filter's intensity, making it as subtle or dramatic as you like. Tweak the brightness, contrast, and saturation until your video looks like you envisioned.

## Part 2: Download External Filter Installation Package

**_Step 1: Locate the My Filters Feature_**

The VN app is awesome, but can you add even more flair to your videos with custom filters? Yup! These aren't just your regular video presets – they're unique styles you can download and add to your VN arsenal.

To begin, tap on the “My Filters” section within the app. If you're wondering where this is, it's usually nestled beside the built-in filter options, represented by a '+' or 'Add' icon. This personal space is ready to be filled with your downloaded filter goodies.

**_Step 2: Import the Downloaded VN Filter APK_**

Here comes the cool part! To get new custom filters:

1. Visit the website or store where the VN filters are available for download. (**Hint:** Search for “vn filter download APK" or "vn iPhone filter download” based on your device.)
2. Once downloaded, head back to the VN app and click the **'Add'** or '+' icon in the **“My Filters”**
3. Navigate to your device's download folder or wherever the vn filter apk is saved.
4. Select the filter file (it should have a .apk or similar extension for Android users and a different format for iPhone users).
5. Tap on **'Import'** and wait for the magic to happen. Your brand-new filter will now be housed in **“My Filters”**!

**_Step 2: Save the Filter Preset and Use It Directly Next Time_**

After importing your snazzy new filter, the next step is super easy. Simply apply it to your video, and if you love how it looks, save it as a preset. This way, the next time you're editing, you can head straight to **"My Filters**," find your favorite custom filter and slap it onto your video without a hitch. Talk about convenience!

## Part 3: Best Alternatives

Though VN offers many fantastic filter options, it's always nice to have alternatives, right? Meet Filmora, another stellar video editing tool known for its expansive video filter collection.

Filmora is more than just an editor; it's a canvas for videographers. One of its most raved-about features is its extensive range of video filters. With Filmora, you can transport your audience from a sun-kissed beach to a moody, rain-soaked alley in just a tap. Whether you’re going for a documentary feel, a Hollywood movie vibe, or something out of a dream, Filmora's filters have covered you.

**Getting started is a breeze:**

1. Launch Filmora and import your video.
2. Head to the **“Effects”** tab and immerse yourself in the filter options.
3. Preview, select, and apply – it’s that simple!
4. Like VN, Filmora allows you to tweak the filter settings for that perfect look.

While Filmora is a great tool, the best fit depends on personal preferences and specific project needs. However, it's always good to have choices in your editing toolkit. Variety is, after all, the spice of life (and video editing)!

## Part 4: Summary

The beauty of video editing lies in the limitless possibilities it offers. With every video filter, editor tweak, and custom preset, you're not just editing – you're storytelling. And with tools like VN and Filmora at your fingertips, you have everything you need to tell your story your way.

Remember, whether you're a seasoned videographer or someone just starting, there's no 'right' or 'wrong' regarding creativity. Play around, experiment, and, most importantly, have fun with the process. In the vast universe of video editing, every filter is a star waiting to shine on your masterpiece.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

## Create Your Own Subscribe Channel Graphics

Professional video creators earn billions from YouTube, Tick Tock, and such platforms today. That strongly encourages newcomers to create their video content. But is it that easy? Of course not. To create a successful video and catch people's attention, subscribe channel graphics are essential.

We have introduced how to create a simple custom subscribe button animation for beginners. We are here to give a more advanced and fully animated graphic that will provide your video with a professional look. Let's start with knowing what a Subscription channel graphic is.

## What Is a Subscribe Channel Graphic?

We here give a simple explanation for those new to a subscribe channel graphic. Have you ever watched videos on a platform like YouTube? If yes, you must have noticed some unique pictures encouraging viewers to subscribe to the channel. That is exactly what a subscribe channel graphic is. It looks like as below.

![a subscribe channel graphic example](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-1.png)

Every video crater incorporates such graphics on their videos before posting them. However, the hardest part is how to create one. We are now moving forward to see how we can make some outstanding subscribe button graphics using Wondershare Filmora.

**Create Advanced Subscription Channel Graphics With Wondershare Filmora**

Before we dive into our step-by-step guide, let's first have an overview of our video editor. [Wondershare Filmora](https://tools.techidaily.com/wondershare/filmora/download/) is an incredible video editor with robust editing features. These features will transform your video into a stunning one within minutes. It also comes with a powerful screen recorder and a large filmstock of templates.

So using these templates, icons, and other features, here are the steps you need to follow to make an advanced subscribe channel graphic.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later

##### Step1 Download and install Wondershare Filmora

First, you need to download and install the video editor, Filmora. If you've already done that, then launch the software right away. But if you haven't, then download it below. Once the download finishes, install the software on your computer.

When you launch the Filmora, click on "New Project."

![new project of wondershare filmora](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-2.png)

##### Step2 Make the structure of your graphics

For creating anything, we first need a flawless structure. Here, we can make the structure of Subscribe channel graphics using different colors, icons, texts, and channel photos. We'll start by adding color layers.

**1\. Add color layers**

* Go to the "Media" on the top left corner of the interface and Click on "Sample Color." Here find the Green color and add it in the panel below as the first video layer by the drag-n-drop function.

![adding a bright green color layer](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-3.png)

* We will key this layer at the end, so make sure not to use any other green graphics for your animation.
* Let's lock this layer because we will no longer use it. For this, click on the "Lock" icon on the layer's left side.
* Add white and red colors and stack them on top of the green color layer.

![white and red color layers added](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-4.png)

After adding all three color layers, it's time to crop these layers to make the structure of our graphic.

##### **Crop the Color Layers**

* Go to the "Effects" tab from the top bar and search for the "Crop" effect. Then drag the effect and add it to the white and red layers on the panel.

![adding the crop effect on color layers](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-5.png)

* First, click on the "Eye" icon beside the red color layer to hide it. Then double-click the white layer to see its properties. When the properties appear, select "Effects" from there.

![cropping the white color layer](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-6.png)

* You can also enable the safe zones from the display settings on the right side of the panel. After that, crop the white layer first, then show the red layer and crop it too. It will look like this.

![enabling the safe zones](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-7.png)

That's it, folks. Our color backgrounds are here. Now we have to add our channel photo to this. So let's move on to see how to do it.

**2\.** **Add a channel photo**

* To add the channel photo, you can upload the image. Here we are going to use some images from the stock media. No matter the image, drop it down on the panel above the red color layer.

![adding an image](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-8.png)

* Now double-click on the image layer, and from the properties, go to the "Mask" option and select the circle. You can also select any other shape you like.

![select a shape for our image](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-9.png)

* After that, scroll down and make the circle even by matching all numbers. Then scale it down and place it on the left corner of the white layer.

![adjusting the channel image](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-10.png)

It's done. Let's add our channel text now.

**3\.** **Add texts**

* For adding text, go to the "Titles" from the top bar and add the title you like to the panel.

![adding the channel text](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-11.png)

* Now double-click this layer and add the text you want. You can also change the color of the text, scale it down and place it where ever you want.

![editing the channel text](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-12.png)

* Now, let's add another title for the subscribe button. You have to place it on the red layer.

![subscribe button text added](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-13.png)

We can't finish our structure without icons, can we? So let's move on to them.

**4\.** **Add icons**

* Hit the "Element" from the top bar and search for the "Bell" icon. You will find the short animations of the bell. Add the suitable one to the panel.

![adding a bell icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-14.png)

* Now find a suitable place in the animation, stop it at that point, right-click on the element layer and add a freeze frame.

![adding a freezeframe of the bell icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-15.png)

* You can also extend the freeze frame and remove the other parts. Then reduce its size and place it beside the "Subscribe" text.

![adjust the bell icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-16.png)

* Similarly, add "Thumbs Up" and "Mouse Cursor" icons on the panel.

![thumbs up and mouse cursor icons added](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-17.png)

Finally, our structure is finished. Now let's start animating.

##### Step3 Animate the graphics

First, we'll make it so that all these graphics come in from below the view.

* Go to the white layer first and double-click on it. Then hit the "Animation" option and scroll down. Here add a new keyframe by clicking "Add." Now move the playhead to the beginning and place the white color layer out of the frame.

![adding a new keyframe on the white color layer](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-18.png)

* Now, do the same for channel photos and icons. The whole animation will look like this.

![successfully animated the graphics](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-19.gif)

* As you can see, the text appears before the color layers. Let's correct it. Double-click the text layer. Select the" Type Writer' form and hit the "Advanced option.

![selecting type writer style for text](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-20.png)

* Here, you can adjust the text with the color layers.

![adjusting the speed of the text](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-21.png)

* After adjusting both the channel name and subscribe button texts, your animation will appear like this.

![the speed of the text adjusted](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-22.gif)

If you've managed so far, then that's great. We have done most of the work. Now we need to animate the graphics of the mouse cursor so that it clicks on the bell icon, thumb icon, and our subscribe button. The process is somewhat similar because we will need to add different keyframes. But still, let's see it in detail.

##### Step4 Animate the mouse cursor

* Go to the "Mouse Cursor" icon layer and double-click on it. First, place the icon on the "Thumbs Up" so that when it animates in, it goes directly to the said icon. Then you have to add another keyframe after some time. And when you add a third one, place the "Mouse Cursor" icon on the subscribe button text.

![adding new keyframes on the mouse cursor icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-23.png)

* Then add a similar pair of keyframes with some space from the last one and place the "Mouse Cursor" icon on the "Bell" icon.

![mouse curson on the bell icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-24.png)

* The last keyframe we have to add will place this "Mouse Cursor" icon out of our view. After that, you need to adjust these keyframes to set the speed of the moving "Mouse Cursor' icon according to your taste.

The final product up till now will be like this.

![successfully animated the mouse cursor icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-25.gif)

We are nearing our end, guys. Now we just need to make the graphics animate out of our view, and our work will be done. So let's dive right into it.

##### Step5 Animate the graphics out

The process of animating out your graphics is like how we animated in our video. We just need to reverse those steps. So here's how it's done.

* Go to the white color layer and double-click on it to open its properties.
* Now, from the "Animation" option, add a new keyframe a little before the end of the video.
* After that, you have to add another keyframe at the end of your video. But in this keyframe, place the white color layer out of your view. Like this,

![removed the white color layer from the frame](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-26.png)

* Repeat the same steps for the red color layer, channel image layer, and icons layer.
* After it's done, the whole graphics will look like this.

![animated the color, image, and icons layers](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-27.gif)

* The only thing that remains is to fix the text layers. For this, double-click on the channel text layer and go to the "Advanced" settings, just like before.

![click on the advanced option](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-28.png)

* From here, fix the text speed and end with your other graphic elements. After it's done, we will do the same for the "Subscribe" button text.

![adjust the text with your graphics](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-29.png)

Finally, our graphic is completed. "Export" it from the software to your computer.

![completed subscribe channel graphics](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-30.png)

Whenever you want to use this graphic on your video, you have to import it first and enable the "Green Screen" option. It will remove the green background color. Then you can upload your video and place this graphic on it to add to the video. And that's all.

## Conclusion

Creating the Subscribe channel graphics is like picking stars from the sky for any video creator, especially if you are a beginner. However, now you don't need to go for the professionals anymore. Wondershare Filmora has got you covered. So follow this detailed guide and create excellent subscribe channel graphics for your videos.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later

##### Step1 Download and install Wondershare Filmora

First, you need to download and install the video editor, Filmora. If you've already done that, then launch the software right away. But if you haven't, then download it below. Once the download finishes, install the software on your computer.

When you launch the Filmora, click on "New Project."

![new project of wondershare filmora](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-2.png)

##### Step2 Make the structure of your graphics

For creating anything, we first need a flawless structure. Here, we can make the structure of Subscribe channel graphics using different colors, icons, texts, and channel photos. We'll start by adding color layers.

**1\. Add color layers**

* Go to the "Media" on the top left corner of the interface and Click on "Sample Color." Here find the Green color and add it in the panel below as the first video layer by the drag-n-drop function.

![adding a bright green color layer](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-3.png)

* We will key this layer at the end, so make sure not to use any other green graphics for your animation.
* Let's lock this layer because we will no longer use it. For this, click on the "Lock" icon on the layer's left side.
* Add white and red colors and stack them on top of the green color layer.

![white and red color layers added](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-4.png)

After adding all three color layers, it's time to crop these layers to make the structure of our graphic.

##### **Crop the Color Layers**

* Go to the "Effects" tab from the top bar and search for the "Crop" effect. Then drag the effect and add it to the white and red layers on the panel.

![adding the crop effect on color layers](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-5.png)

* First, click on the "Eye" icon beside the red color layer to hide it. Then double-click the white layer to see its properties. When the properties appear, select "Effects" from there.

![cropping the white color layer](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-6.png)

* You can also enable the safe zones from the display settings on the right side of the panel. After that, crop the white layer first, then show the red layer and crop it too. It will look like this.

![enabling the safe zones](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-7.png)

That's it, folks. Our color backgrounds are here. Now we have to add our channel photo to this. So let's move on to see how to do it.

**2\.** **Add a channel photo**

* To add the channel photo, you can upload the image. Here we are going to use some images from the stock media. No matter the image, drop it down on the panel above the red color layer.

![adding an image](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-8.png)

* Now double-click on the image layer, and from the properties, go to the "Mask" option and select the circle. You can also select any other shape you like.

![select a shape for our image](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-9.png)

* After that, scroll down and make the circle even by matching all numbers. Then scale it down and place it on the left corner of the white layer.

![adjusting the channel image](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-10.png)

It's done. Let's add our channel text now.

**3\.** **Add texts**

* For adding text, go to the "Titles" from the top bar and add the title you like to the panel.

![adding the channel text](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-11.png)

* Now double-click this layer and add the text you want. You can also change the color of the text, scale it down and place it where ever you want.

![editing the channel text](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-12.png)

* Now, let's add another title for the subscribe button. You have to place it on the red layer.

![subscribe button text added](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-13.png)

We can't finish our structure without icons, can we? So let's move on to them.

**4\.** **Add icons**

* Hit the "Element" from the top bar and search for the "Bell" icon. You will find the short animations of the bell. Add the suitable one to the panel.

![adding a bell icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-14.png)

* Now find a suitable place in the animation, stop it at that point, right-click on the element layer and add a freeze frame.

![adding a freezeframe of the bell icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-15.png)

* You can also extend the freeze frame and remove the other parts. Then reduce its size and place it beside the "Subscribe" text.

![adjust the bell icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-16.png)

* Similarly, add "Thumbs Up" and "Mouse Cursor" icons on the panel.

![thumbs up and mouse cursor icons added](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-17.png)

Finally, our structure is finished. Now let's start animating.

##### Step3 Animate the graphics

First, we'll make it so that all these graphics come in from below the view.

* Go to the white layer first and double-click on it. Then hit the "Animation" option and scroll down. Here add a new keyframe by clicking "Add." Now move the playhead to the beginning and place the white color layer out of the frame.

![adding a new keyframe on the white color layer](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-18.png)

* Now, do the same for channel photos and icons. The whole animation will look like this.

![successfully animated the graphics](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-19.gif)

* As you can see, the text appears before the color layers. Let's correct it. Double-click the text layer. Select the" Type Writer' form and hit the "Advanced option.

![selecting type writer style for text](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-20.png)

* Here, you can adjust the text with the color layers.

![adjusting the speed of the text](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-21.png)

* After adjusting both the channel name and subscribe button texts, your animation will appear like this.

![the speed of the text adjusted](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-22.gif)

If you've managed so far, then that's great. We have done most of the work. Now we need to animate the graphics of the mouse cursor so that it clicks on the bell icon, thumb icon, and our subscribe button. The process is somewhat similar because we will need to add different keyframes. But still, let's see it in detail.

##### Step4 Animate the mouse cursor

* Go to the "Mouse Cursor" icon layer and double-click on it. First, place the icon on the "Thumbs Up" so that when it animates in, it goes directly to the said icon. Then you have to add another keyframe after some time. And when you add a third one, place the "Mouse Cursor" icon on the subscribe button text.

![adding new keyframes on the mouse cursor icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-23.png)

* Then add a similar pair of keyframes with some space from the last one and place the "Mouse Cursor" icon on the "Bell" icon.

![mouse curson on the bell icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-24.png)

* The last keyframe we have to add will place this "Mouse Cursor" icon out of our view. After that, you need to adjust these keyframes to set the speed of the moving "Mouse Cursor' icon according to your taste.

The final product up till now will be like this.

![successfully animated the mouse cursor icon](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-25.gif)

We are nearing our end, guys. Now we just need to make the graphics animate out of our view, and our work will be done. So let's dive right into it.

##### Step5 Animate the graphics out

The process of animating out your graphics is like how we animated in our video. We just need to reverse those steps. So here's how it's done.

* Go to the white color layer and double-click on it to open its properties.
* Now, from the "Animation" option, add a new keyframe a little before the end of the video.
* After that, you have to add another keyframe at the end of your video. But in this keyframe, place the white color layer out of your view. Like this,

![removed the white color layer from the frame](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-26.png)

* Repeat the same steps for the red color layer, channel image layer, and icons layer.
* After it's done, the whole graphics will look like this.

![animated the color, image, and icons layers](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-27.gif)

* The only thing that remains is to fix the text layers. For this, double-click on the channel text layer and go to the "Advanced" settings, just like before.

![click on the advanced option](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-28.png)

* From here, fix the text speed and end with your other graphic elements. After it's done, we will do the same for the "Subscribe" button text.

![adjust the text with your graphics](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-29.png)

Finally, our graphic is completed. "Export" it from the software to your computer.

![completed subscribe channel graphics](https://images.wondershare.com/filmora/article-images/2022/12/how-to-create-your-own-subscribe-channel-graphics-30.png)

Whenever you want to use this graphic on your video, you have to import it first and enable the "Green Screen" option. It will remove the green background color. Then you can upload your video and place this graphic on it to add to the video. And that's all.

## Conclusion

Creating the Subscribe channel graphics is like picking stars from the sky for any video creator, especially if you are a beginner. However, now you don't need to go for the professionals anymore. Wondershare Filmora has got you covered. So follow this detailed guide and create excellent subscribe channel graphics for your videos.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

## How to Rotate Videos With Media Player Classic

The Internet and social media have become a staple in our daily lives. Internet users post thousands of videos every day that you can watch online or download and rewatch in your free time. Suppose you encounter a video that is upside down or shot at an angle that makes it difficult for you to enjoy it fully.

It would be nice to find a way to rotate the video to portrait mode so you can watch it without any distractions. Fortunately, this article will discuss using Media Player Classic to rotate any video. We also discuss an excellent alternative to the aforementioned media player.

![rotate videos with media player classic](https://images.wondershare.com/filmora/article-images/media-player-classic-rotate.JPG)

## What Is Media Player Classic?

In a nutshell, Media Player Classic is an open-source media player suitable for 32-bit and 64-bit Microsoft Windows. If you have used the original interface, you might notice that it resembles Windows Media Player 6.4\. The only key difference is that the former is more feature-rich and provides more options. In addition, Media Player Classic is very compact and lightweight.

![media player classic interface](https://images.wondershare.com/filmora/article-images/media-player-classic.jpg)

A programmer named "Gabest'' created and designed this platform as a closed-source application. Things changed, and he later relicensed the media player as free under the terms of the GLP-2.0 license. He released the final version, MPC 6.4.9.0, on 20th March 2006.

Unfortunately, development stalled in 2006, much to the disappointment of many users who had grown to love it. Gabest made a public statement in 2007 saying that Media Player Classic was not dead, just that he couldn't work on it anymore.

## How To Rotate Video in Media Player Classic?

Media Player Classic allows you to rotate your video around three axes, X, Y, and Z. Once you are done, you can fix a video that was initially upside down or in landscape mode for a better viewing experience. Another perk of using Media Player Classic to rotate a video is that you can use shortcuts to make your work easier.

Before we teach you how to rotate video in windows Media Player Classic, there are a few things you should know. Unfortunately, this platform doesn't allow you to rotate a video in its graphical user interface. You can't also use it to edit a video. Suppose you want to add text or overwrite the original video clip. Media Player Classic can only allow you to playback a video or rotate it.

Here is a simple guide on how to rotate videos in Media Player Classic.

Step1 Launch Media Player Classic and click on the "View" tab. Select "Options" or click "O" to display the "Options" window.

![options in media player classic](https://images.wondershare.com/filmora/article-images/media-player-classic-options.jpg)

Step2 Navigate to the left pane to the Player Group and click on "Keys." If the Player Group is not expanded by the time, you launch the platform, double-click it and wait a few seconds. You can then navigate to the "PnS Rotate" command on the Keys list.

![keys in media player classic](https://images.wondershare.com/filmora/article-images/media-player-classic-keys.jpg)

Step3 Go to the "PnS Rotate+" command and double-click the "Key" field. You can then click on any key to rotate your video around the x-axis. Once you are satisfied with the results, click "…" to apply the changes you have made.

![pns rotate in media player classic](https://images.wondershare.com/filmora/article-images/media-player-classic-pns-rotate.jpg)

Step4 You can now assign shortcuts to "PnS Rotate" commands. For instance, you could assign PnS Rotate Y for rotation along the Y axis and PnS Z for rotation along the Z axis. After each axis has a shortcut, select "Apply" then "OK" to save your changes and close the Options window respectively.

![apply rotate in media player classic](https://images.wondershare.com/filmora/article-images/media-player-classic-apply.jpg)

Step5 Select "Output" on the Options window and navigate to the DirectShow Video section to confirm whether the Media Classic Player supports rotation for the rendered video. Ascertain the Rotation feature has a green check mark, which indicates that the platform promotes rotation for the video. If the video has a red X, select "Apply" and click "OK."

![output rotation in media player classic](https://images.wondershare.com/filmora/article-images/media-player-classic-output.jpg)

Step6 Use the shortcuts you assigned to the keys in Step 4 to rotate your video as you see fit. Since the rotation occurs gradually, you might need to press the keys numerous times or press and hold to see a visible change.

For instance, you can rotate your video from landscape to portrait by clicking "Alt-Num 1" and "Alt-Num 3," respectively. To revert your video to its original state, press "Alt-Num 5."

## Need an alternative to Media Player Classic? Try [Wondershare Filmora](https://tools.techidaily.com/wondershare/filmora/download/) To Rotate a Video

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later

You might need a better alternative to Media Classic Player to help rotate your videos. As we mentioned, Media Classic Player doesn't allow you to change the video. The scope of this platform only extends to playing and rotating videos along three axes. In our opinion, Wondershare Filmora is an excellent alternative.

![wondershare filmora](https://images.wondershare.com/filmora/guide/startup-window-on-windows-01.png)

This feature-rich platform is your one-stop solution for any creator who wants to make a mark with their videos. You can download it free on your desktop, laptop, or smartphone and use it anytime. The cloud storage allows you to snap a photo and upload it for editing at a later time.

In addition, the platform has a co-creation space where you can share your work with other users and compare notes. Here is a list of other nifty features we guarantee you will enjoy.

* Motion tracking
* Auto beat sync
* Split screen
* Title Editing
* Preset templates
* AI Portrait
* Mask and blend
* Text to speech
* Silence detection
* Audio visualizer

## How To Rotate a Video 90 Degrees With Wondershare Filmora?

Now that you have seen how different this platform is from Media Classic Player, you might be curious about how effectively it rotates your videos. Perhaps our detailed guide will help you decide whether you want to give Wondershare Filmora a shot.

Stick around to learn how to rotate a video 90 degrees with Wondershare Filmora.

Step1 Import the video you want to rotate to Wondershare Filmora and drag and drop it to the timeline as shown below.

![add media to timeline wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-add-to-timeline-rotate.jpg)

Step2 Click on the monitor icon and select "Change Project Aspect Ratio" in the drop-down menu.

![change project aspect ratio wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-change-project-ratio-rotate.jpg)

Step3 In the "Project Settings" window, you can change your video's Aspect Ratio, Resolution, Frame Rate, and Color space.

![select aspect ratio wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-select-aspect-ratio-rotate.jpg)

Step4 Once you are happy with your changes, click "OK" and close the window.

![project settings wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-project-settings-rotate.jpg)

Step5 Double-click the video track and navigate to the Rotate option in the window. Hover your mouse over the dot in the Rotate tab until you get to 90 degrees. You could also adjust the rotation of the video by clicking on the pivot in the media player till the video is at 90 degrees.

![rotate video wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-rotate-video-settings.jpg)

Step6 Click "Export" to save a copy of the rotated video to your device.

![export video wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-export-video-rotate.jpg)

## Which Is Better To Rotate a Video? Media Player Classic or Wondershare Filmora?

Having seen both sides of the coin, you might wonder which option is better to help you rotate a video. In this section of the article, we pit Wondershare Filmora against Media Player Classic to help you determine which option will work best for you.

Take a look at the table below.

| **Media Player Classic** | **Wondershare Filmora**                                                                                                   |                                                                                                                                                                    |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Operating System**     | Microsoft Windows                                                                                                         | Windows & Mac                                                                                                                                                      |
| **Ratings from G2**      | N/A                                                                                                                       | [4.4/5 stars](https://www.g2.com/products/wondershare-filmora/reviews)                                                                                             |
| **Pricing**              | Free                                                                                                                      | Annual Plan – US$49.99/yearCross Platform Plan - US$59.99/YearPerpetual Plan - US$79.99                                                                            |
| **Features**             | ● Enhanced video rendering● Removal of tearing● Supports SVCD, VCD, and DVD playback● AVI subtitles● Customizable toolbar | ● AI Portrait● Mask and blend● Text to speech● Silence detection● Audio visualizer● Motion tracking● Auto beat sync● Split screen● Title Editing● Preset templates |

As you have seen, Media player Classic doesn't have the Rotate feature per se. However, you can assign shortcuts to the keys to rotate a video along three axes as you see fit. You can also use a combination of keys like Alt and Num to change how your video sits so you can enjoy it as you like.

On the other hand, Wondershare Filmora has a more comprehensive Rotate feature that allows you to drag your pointer along a bar till the video sits at the correct number of degrees.

This platform also provides additional features, like allowing you to scale the video to fit the screen and adjusting project settings like the resolution and frame rate. If you don't want to use the sliding bar, you can use your pointer to manually adjust the rotation by clicking on the pivot with your pointer.

In a nutshell, Windows Media Player is the ideal choice if you want to rotate your video and leave it at that. However, if you are looking for more advanced features, you are better off choosing Wondershare Filmora. The latter option also makes your videos look more polished like they were edited by a professional.

## Conclusion

Videos might be trickier to edit than photos, especially when you want to rotate them. Fortunately, developers have been working tirelessly to ensure you have many tools at your disposal to edit your videos from any device at any time.

If you don't fancy editing videos on your laptop, you could download the software to your smartphone and rotate videos on the move. Technology is truly a blessing that has come to make our work easier. Hopefully, after reading this article, you can effortlessly rotate any video you encounter.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later

You might need a better alternative to Media Classic Player to help rotate your videos. As we mentioned, Media Classic Player doesn't allow you to change the video. The scope of this platform only extends to playing and rotating videos along three axes. In our opinion, Wondershare Filmora is an excellent alternative.

![wondershare filmora](https://images.wondershare.com/filmora/guide/startup-window-on-windows-01.png)

This feature-rich platform is your one-stop solution for any creator who wants to make a mark with their videos. You can download it free on your desktop, laptop, or smartphone and use it anytime. The cloud storage allows you to snap a photo and upload it for editing at a later time.

In addition, the platform has a co-creation space where you can share your work with other users and compare notes. Here is a list of other nifty features we guarantee you will enjoy.

* Motion tracking
* Auto beat sync
* Split screen
* Title Editing
* Preset templates
* AI Portrait
* Mask and blend
* Text to speech
* Silence detection
* Audio visualizer

## How To Rotate a Video 90 Degrees With Wondershare Filmora?

Now that you have seen how different this platform is from Media Classic Player, you might be curious about how effectively it rotates your videos. Perhaps our detailed guide will help you decide whether you want to give Wondershare Filmora a shot.

Stick around to learn how to rotate a video 90 degrees with Wondershare Filmora.

Step1 Import the video you want to rotate to Wondershare Filmora and drag and drop it to the timeline as shown below.

![add media to timeline wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-add-to-timeline-rotate.jpg)

Step2 Click on the monitor icon and select "Change Project Aspect Ratio" in the drop-down menu.

![change project aspect ratio wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-change-project-ratio-rotate.jpg)

Step3 In the "Project Settings" window, you can change your video's Aspect Ratio, Resolution, Frame Rate, and Color space.

![select aspect ratio wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-select-aspect-ratio-rotate.jpg)

Step4 Once you are happy with your changes, click "OK" and close the window.

![project settings wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-project-settings-rotate.jpg)

Step5 Double-click the video track and navigate to the Rotate option in the window. Hover your mouse over the dot in the Rotate tab until you get to 90 degrees. You could also adjust the rotation of the video by clicking on the pivot in the media player till the video is at 90 degrees.

![rotate video wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-rotate-video-settings.jpg)

Step6 Click "Export" to save a copy of the rotated video to your device.

![export video wondershare filmora](https://images.wondershare.com/filmora/article-images/filmora-export-video-rotate.jpg)

## Which Is Better To Rotate a Video? Media Player Classic or Wondershare Filmora?

Having seen both sides of the coin, you might wonder which option is better to help you rotate a video. In this section of the article, we pit Wondershare Filmora against Media Player Classic to help you determine which option will work best for you.

Take a look at the table below.

| **Media Player Classic** | **Wondershare Filmora**                                                                                                   |                                                                                                                                                                    |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Operating System**     | Microsoft Windows                                                                                                         | Windows & Mac                                                                                                                                                      |
| **Ratings from G2**      | N/A                                                                                                                       | [4.4/5 stars](https://www.g2.com/products/wondershare-filmora/reviews)                                                                                             |
| **Pricing**              | Free                                                                                                                      | Annual Plan – US$49.99/yearCross Platform Plan - US$59.99/YearPerpetual Plan - US$79.99                                                                            |
| **Features**             | ● Enhanced video rendering● Removal of tearing● Supports SVCD, VCD, and DVD playback● AVI subtitles● Customizable toolbar | ● AI Portrait● Mask and blend● Text to speech● Silence detection● Audio visualizer● Motion tracking● Auto beat sync● Split screen● Title Editing● Preset templates |

As you have seen, Media player Classic doesn't have the Rotate feature per se. However, you can assign shortcuts to the keys to rotate a video along three axes as you see fit. You can also use a combination of keys like Alt and Num to change how your video sits so you can enjoy it as you like.

On the other hand, Wondershare Filmora has a more comprehensive Rotate feature that allows you to drag your pointer along a bar till the video sits at the correct number of degrees.

This platform also provides additional features, like allowing you to scale the video to fit the screen and adjusting project settings like the resolution and frame rate. If you don't want to use the sliding bar, you can use your pointer to manually adjust the rotation by clicking on the pivot with your pointer.

In a nutshell, Windows Media Player is the ideal choice if you want to rotate your video and leave it at that. However, if you are looking for more advanced features, you are better off choosing Wondershare Filmora. The latter option also makes your videos look more polished like they were edited by a professional.

## Conclusion

Videos might be trickier to edit than photos, especially when you want to rotate them. Fortunately, developers have been working tirelessly to ensure you have many tools at your disposal to edit your videos from any device at any time.

If you don't fancy editing videos on your laptop, you could download the software to your smartphone and rotate videos on the move. Technology is truly a blessing that has come to make our work easier. Hopefully, after reading this article, you can effortlessly rotate any video you encounter.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





