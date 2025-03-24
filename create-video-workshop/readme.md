# Create your first HowTo video workshop
This workshop teaches you how to make a demo video of our own. From the conceptual stage of figuring out what type of video you intend to create, to the script writing stage, and finally to recording it. You will walk through this entire process with step-by-step instructions after watching the presenter perform the steps first. By the end of this workshop, you should all have a working video demo to show for it.

To watch a replay of this workship, see this video: https://ibm.box.com/s/ruhqv1iorqomuskzpc89y4ku2mhcg4of

## Workshop overview
This workshop covers the following topics:
- [General process for creating videos](#general-process-for-creating-videos)
- [Prerequisites](#prerequisites)
- [Task 1: Create a test project in CPDaaS](#task-1-create-a-test-project-in-cpdaas)
- [Task 2: Write the script](#task-2-write-the-script)
- [Task 3: Set up Camtasia](#task-3-set-up-camtasia)
- [Task 4: Make the video recordings](#task-4-make-the-video-recordings)
- [Task 5: Record the audio](#task-5-record-the-audio)
- [Task 6: Synchronize the video and audio](#task-6-synchronize-the-video-and-audio)
- [Task 7: Publish the video](#task-7-publish-the-video)
- [Task 8: Generate closed captions](#task-8-generate-closed-captions)
- [Task 9: Embed your video in the doc topic](#task-9-embed-your-video-in-the-doc-topic)
- [Earn a badge](#optional-earn-a-badge)

## General process for creating videos
1. Write the script.
    1) Research the feature.
    1) Draft the script.
    1) Get the script reviewed.
    1) Incorporate review feedback.
1. Develop video.
   1) Capture the video recordings.
   1) Record the audio.
   1) Edit the video.
   1) Produce the draft video.
   1) Get the draft video reviewed.
   1) Incorporate feedback.
1. Produce the final video.
   1) Generate closed captions.
   1) Publish video and captions to the hosting site.
   
## Prerequisites
Prior to attending this workshop, you will need to:
1. Sign up for a Cloud Pak for Data as a Service account, if you don't already have one: <a href="https://dataplatform.cloud.ibm.com/registration/stepone?context=cpdaas&apps=all" target="_blank">https://dataplatform.cloud.ibm.com/registration/stepone?context=cpdaas&apps=all</a> - use your IBM email address to sign up.
1. Download the free trial version of Camtasia 2021, if you don't already have it installed: <a href="https://www.techsmith.com/download/camtasia/" target="_blank">https://www.techsmith.com/download/camtasia/</a>
1. (Optional) Watch this intro to how video fits in to Data & AI Content Design: <a href="https://ibm.box.com/s/q5tslvtk07rrnlf8jd2d2yr89asjk6q9" target="_blank">https://ibm.box.com/s/q5tslvtk07rrnlf8jd2d2yr89asjk6q9</a>

## Task 1: Create a test project in CPDaaS
Follow these steps to create a test project and write the script in the process.
1. From the CPDaaS home screen, click **Create a project**.
1. Select **Create an empty project**.
1. Provide a name for the test project.
1. Provide a description for the test project.
1. Click **Create**.
1. Review each of the tabs in the new project. Refer to these doc topics for details on each tab.
    - <a href="https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/projects.html" target="_blank">https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/projects.html</a>
    - <a href="https://dataplatform.cloud.ibm.com/docs/content/wsj/manage-data/manage-assets.html" target="_blank">https://dataplatform.cloud.ibm.com/docs/content/wsj/manage-data/manage-assets.html</a>
    - <a href="https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/environments-parent.html" target="_blank">https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/environments-parent.html</a>
    - <a href="https://dataplatform.cloud.ibm.com/docs/content/wsj/manage-data/jobs.html" target="_blank">https://dataplatform.cloud.ibm.com/docs/content/wsj/manage-data/jobs.html</a>
    - <a href="https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/collaborate.html" target="_blank">https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/collaborate.html</a>
    - <a href="https://dataplatform.cloud.ibm.com/docs/content/wsj/manage-data/admin-project.html" target="_blank">https://dataplatform.cloud.ibm.com/docs/content/wsj/manage-data/admin-project.html</a>
    
## Task 2: Write the script

### Tips for writing a script
#### Consider what type of script are you writing
Your writing style and approach varies depending on what kind of script you'll be writing.
- HowTos are similar to the standard procedural documentation that you're used to, but less formal. A procedure shows how to complete a specific task where you both show and describe steps to a user. Example: <a href="http://ibm.biz/cpdaas-videos
">http://ibm.biz/cpdaas-videos</a>
- Service/feature overviews are at a high level, with little task information. This conceptual information is meant to be a demonstration to show users what is available to them in the product, and usually includes minimal steps or none at all. Example: <a href="https://www.ibm.com/docs/en/cloud-paks/cp-data/3.5.0?topic=governance-watson-knowledge-catalog">https://www.ibm.com/docs/en/cloud-paks/cp-data/3.5.0?topic=governance-watson-knowledge-catalog</a>
- What's new videos highlight the changes from one release to the next. Example: <a href="https://ibm.biz/cloud-pak-for-data-35-learning">https://ibm.biz/cloud-pak-for-data-35-learning</a>

#### Strike the right tone
A howto video is a demonstration. Imagine for a second that you're showing a coworker how to perform a task in Watson Studio, or showing the cool new features in the new version of Cloud Pak for Data. You'd be using a more relaxed tone than you use with standard procedural documentation. Another way to describe this tone would be "conversational". Thinking of the script more as writing a dialogue, especially when using personas, can help. Also, things like contractions can make a written conversation sound more realistic.
Stick with an active voice and present tense. Remember, you're talking about things that are happening now in the video. When you're writing a script, this informality plays an important role, especially with the narration text.<br />
<br />
For example:<br />
<br />
Instead of: "The system displays the Primary Model window. This window shows the blank model that can be used to import data from a DB2, Cloudscape, or Oracle database."<br />
Try: "Now, look at the model you'll be using to import data from your database."<br />
<br />
or<br />
<br />
Instead of: "Now that the meeting has ended"<br />
Try: "Now that you ended the meeting"<br />
<br />
Note that we're using a second person narration. I'm talking to the viewer about something that he/she will be doing. This tone helps users feel that a coworker is showing them how to complete the task, rather than just having someone read a manual to them. It is often helpful to speak the narration parts out loud to see if they sound natural and flow well.<br />
<br />
Avoid phrases, expressions, or colloquialisms that are likely to be misunderstood or are culture-specific when using a casual tone.<br />
<br />
Instead of: "check out"<br />
Try: "take a look at"<br />
<br />
Remember, you're not describing exact steps for users to follow like in standard procedure documentation. You can summarize action, for example:<br />
<br />
Instead of: "Click File -> New ->Model, and click OK."<br />
Try: "Next, create a new model."<br />
<br />
We summarize here because users can see what we're talking about. If detail is critical, the detail text could be a caption.

#### Consider length
When you complete your run-through, try to time the sequences to get a general sense of how long the video will run. You can trim the video clips to compress a sequence that has a lot of dead time. You can also shorten a video by:
- Skip over sections that you don't need to repeat. For example, if you've already shown how to save something or run or test something in the video, then you don't need to repeat it. You can say something like "As you did in the last step, save and run the model. Now here are the new results."
- Consider reducing wordiness, especially if the action that you're describing in text is also being shown in the video. Pause the video action to allow enough time for users to read the caption or for the narrator to read the text.

#### Think visually
Learn to visualize how the pieces fit together into a story, so that the video "speaks" in addition to the words in the script speaking, it may be a new skill set for you and that can take time to learn, but will yield positive results for users.

### Write the script
Complete the following table with the audio and actions on screen to create a project. Include specific actions with text to enter, buttons to click, and so on. Also include any screen elements to highlight and information the user will find helpful in making decisions about which options to select. (Optional) When the project is created, provide a brief overview of each tab in the project.
Step | Audio | Actions on screen
---- | ----  | -----------------
1 | One sentence explaining what the video shows you how to do. | Intro screen with offering name, video title, copyright, and logo displays.
2 | - | -
3 | - | -
4 | - | -
5 | - | -
6 | Find more videos in the Cloud Pak for Data as a Service documentation. | Outro screen with IBM logo, copyright, and call-to-action URL displays.

### Test your script in the real environment
It's important that you try your scripts out in your environment before starting to record. A thorough test reveals unforeseen pop-ups, error messages, missing data, etc.<br />
<br />

#### Checkpoint
If you didn't finish your script, you can use the <a href="https://github.ibm.com/sharyn-richard/tutorials/blob/master/create-video-workshop/sample-script-short.md" target="_blank">short sample script</a> to continue with the workshop. The <a href="https://github.ibm.com/sharyn-richard/tutorials/blob/master/create-video-workshop/sample-script-long.md" target="_blank">long sample script</a> includes a description of each tab in the project.

## Task 3: Set up Camtasia
Follow these steps to set up Camtasia.
1. Download the appropriate template and theme from here: <a href="https://ibm.box.com/s/xrnlvh4xpb0md0omw6g6cf9p5gxxzu2r" target="_blank">https://ibm.box.com/s/xrnlvh4xpb0md0omw6g6cf9p5gxxzu2r</a> - save the files to the Camtasia folder on your laptop.
1. Start **Camtasia**.
1. Select **New from template**.
1. Click the plus sign (**+**), select the template, and click **Open**.
1. Select the template you imported early, and click **New from Template**. If you received a message to convert the project to the latest version, click **Yes**.
1. The template includes an intro, outro, and a sample rectangle callout. Double-click the purple rectangle on the timeline to see the *Properties* panel.
1. Click the *Theme* drop-down box, and choose **Manage Themes**.
1. Click the **Settings** menu, and select **Import theme**.
1. Select the theme, and click **Open**.
1. Close the *Themes* dialog box.
1. Click **File->Save**, and save the project to the desired folder.

## Task 4: Make the video recordings
### Video recording best practices
- An external monitor is a huge plus - it provides the appropriate 16:9 aspect ratio for HD videos (whereas Mac laptops are 16:10 aspect ratio).
- Don't worry about making mistakes, they can be edited out.
- Record in relatively short segments (<2 minutes).

### Create the video recording
Follow these steps to make the video recordings.
1. Set your screen resolution to something close to 1920x1080 (Windows) and 2880x1800 (Mac).
1. Open CPDaaS to the home screen.
1. In Camtasia, click **Record**.
1. Set up the recorder:
   1. On a Mac, you may need to grant permission to record the screen. Click the tile for **Permission** to launch the *Settings*. Select **Camtasia 2024** to grant permission for *Screen Recording*.
   1. Set the recording area to Full screen which should show your resolution. If you have multiple monitors, you will need to select which screen you want to record.
   1. Turn off the camera, microphone, and system audio.
   1. (Windows only) Click **Tools->Options**.
   1. (Windows only) Select **Prompt for file name**.
   1. (Windows only) Click **OK**.
1. Set the browser to full screen - no address bar, no browser tabs, no bookmarks bar, and no operating system menus/tasks bar. If you are on a Mac, you may need to display the option to **Always Show Toolbar in Full Screen** in your browser.
1. Keyboard shortcuts to use:
   1. Start/Pause the recording: **F9** (Windows) and **Cmd+Shift+2** (Mac).
   1. Stop the recording: **F10** (Windows) and **Cmd+Option+2** (Mac).
1. Start the recording, and follow the steps in the **Actions on screen** column in your script. If you make mistakes, you can usually edit that out. If there's a lot of wait time, you can also edit that out (or speed it up depending on what's appropriate).
1. Stop the recording. and save the file with a descriptive name and in a folder where you will be editing the video.

## Task 5: Record the audio
### Audio recording best practices
When you record the audio from your script, consider the following tips:
- Record the audio in short snippets, for example, each step is it's own audio file. This will make it easier to update the audio at a later date if necessary.
- Use a headset with a microphone or a desktop microphone. Do not use the laptop microphone as there will be too much background noise.
- Use the audio software to adjust the volume and remove the background noise.
- You can use Camtasia to record the audio, or if you have a favorite audio editor such as Audacity, you can use that.

### Create the audio recordings
Follow these steps to record the audio using Camtasia.
1. In Camtasia, select **Voice Narration** from the side navigation.
1. Select your microphone from the drop-down list.
1. (Windows only) Make sure the **auto leveling** icon is turned on.
1. Click **Start Voice Recording**.
1. Read the text from your script in the audio column for step 1, and stop the recording.
1. (Windows only) Save the recording as **step01.m4a**.
1. Repeat this process to record the rest of the script. When you done, you should have as many audio files as you have steps in the table.

#### Checkpoint
If you did not finish your video audio recordings, you can download the samples from here:<br />
- <a href="https://github.ibm.com/sharyn-richard/tutorials/blob/master/create-video-workshop/create-project-audio-files.zip" target="_blank">audio files</a><br />
- <a href="https://github.ibm.com/sharyn-richard/tutorials/blob/master/create-video-workshop/create-project-video-recording.zip" target="_blank">video files</a><br />

## Task 6: Synchronize the video and audio
### Synchronization tips
- Delete sections to shorten UI load times
- Split video recordings to make changes to a section of video
- Add clip speed to speed up sections of video

Follow these steps to synchronize the video and audio.
1. Add the video recording to **Track 3** on the timeline after the intro. **Note:** You will need to move the example shape and outro out of the way. You can do that by grouping the outro elements together and moving them to Track 1, and then hiding that track.
1. Add the first audio file and adjust the length of the intro to match the step 1 audio recording.
1. Repeat this process using the Cut and Clip speed features to adjust to the video and audio recordings to synchronize the two.

## Task 7: Publish the video
When you've completed your editing, you'll want to publish the video to mp4 format for review. Follow these steps to publish the video.
1. Choose **Export->Local File**.
1. Select **Mp4 only (up to 1080p)** (Windows) or Export to MP4 (Mac) from the drop-down list.
    1. (Windows) Click **Next**.
1. Browse to select a folder for the mp4 file, and (Windows) choose if you want Camtasia to organize the produced files into sub-folders. **Note:** The production name should be filled in for you to match the project name.
1. (Windows) Choose the desired post production options.
1. Click **Finish** (Windows) or **Export** (Mac).
<br />
Review the mp4 once more and make any additional edits before posting it to Box for others to review. It's a best practice to embed the box video into the boxnote that contains the script. Reviewers can watch the video and add their review comments to the boxnote.

## Task 8: Generate closed captions
### Closed captions considerations
Closed captions are required for accessibility compliance. There are two options for generating the captions:
- (Auto-generate) Watson Media does auto-generate captions for uploaded videos using Watson Speech to Text; however, there is no punctuation and no capitalization, so you would need edit the captions auto-generated by Watson Media.
- (Manually generate) You can manually generate the captions. Since you have a script already written out, it's just as easy to manually generate the captions.

### Tips and best practices
- It would be helpful to remove any blank lines from the script before you paste it into Camtasia.
- Try to keep complete sentences in a single caption, unless the sentence is too long and it's not possible to fit on a single caption.
- Captions can be tricky. This <a href="https://www.techsmith.com/tutorial-camtasia-manually-add-captions-to-a-video.html" target="_blank">Manually add captions to a video</a> could be helpful.

### Create the captions file
(Windows only) Follow these steps to create the captions file in Camtasia.
1. Select **Captions** from the left side panel (Windows).
1. Place the timeline marker at the beginning of the timeline, and click **Add Caption**.
1. Copy the **Audio** column from your script, and paste it into the *Blank Caption* area.<br />
1. From the *Captions Settings* menu, select **Sync captions**.
1. Listen to the audio play, and click on the corresponding work to sync the captions. 
1. When done syncing, click **Stop**.
1. From the *Captions Settings* menu, select **Export captions**, and save the captions file using the **SMI format**.

## Task 9: Embed your video in the doc topic
Follow these steps to embed your video in a doc topic.
- For markdown topics: https://moon1.fyre.ibm.com:8950/docs/content/wsj/wscommon/cheatsheet.html?context=analytics&audience=wdp#videos
- For DITA topics: https://ibmdocs-test.dcs.ibm.com/docs/en/SSQNUZ_5.0_test?topic=guidelines-embed-accessible-videos

## Optional: Earn a badge
Complete the <a href="https://learn.ibm.com/course/view.php?id=5426'">Creating IBM Digital Video course</a> to earn a badge.
