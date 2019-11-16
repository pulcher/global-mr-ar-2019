# global-mr-ar-2019
Workshop for the Global AR/MR Bootcamp 2019

## Prereq's
* An Azure account http://azure.com
    For a free azure acount signup here: https://azure.microsoft.com/en-us/free/?WT.mc_id=A261C142F

* Visual Studio 2019 Community https://visualstudio.microsoft.com/

## Making and Training Models.... the easy way

Get started by going to https://www.customvision.ai/

Sign in and you will be taken to the projects screen

Follow the direction presented here: 
https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/get-started-build-detector

There are a number of steps on a number of pages.

Your final step will be to export the model.  You can find those steps here: https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/export-your-model

After you export your model, extract the zip file and check the contents.

## Free Images to use for training
Since images do have ownership I like to use any creative common type images for my testing.  You can find a number of those images here:
* https://commons.wikimedia.org/wiki/Pizza
* https://commons.wikimedia.org/wiki/Coffee_pot
* https://commons.wikimedia.org/wiki/Toaster
* https://commons.wikimedia.org/wiki/Category:Canoes
* https://commons.wikimedia.org/wiki/Teddy_bear

## How might you use the trained model?
Open up the solution in .\global-mr-ar-2019\DeepLearning_ObjectDetection_Onnx

Clean out the folder Assets\Output

Hit the F5 key to build and run the example.

This uses a pre-trained model called TinyYolo2.  This model is limited, but can detect a lot of objects.

Go back to the Assets\Output and there should now be processed files there.  Open them in your favorite image editor to see what the process found.

## Yeah, but what about the model I just built?
Open up the solution in .\global-mr-ar-2019\cognitive-services-onnx-customvision-sample

You may need to Install/Update the latest Nuget packages.

Hit F5 to build and run the solutions.  There are a number of sample images that will work with the current model.

It is an exercise for the student to integrate their model into this solution.  There are basic instructions. 

You should use these as examples to what can be done with local models.

You can also use the models through and API.

