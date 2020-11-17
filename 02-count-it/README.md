# Count It

This section we will take another basic sample to understand what goes into implementing an application that takes a Revit file as input and extract information from it. This will also teach how to pass in parameters to the job, in a way that your application conditionally react to those parameters. You will learn to use Newtonsoft, a nuget library to serialize and deserialize your data to pass over the network and post it in a workitem argument.

This application is simple to understand and uses very basic Revit API routines to count number of elements of an input category list. You will learn about how to provide inputs and generate outputs that are both not Revit files.

This is a great start for anyone looking to build data extraction from Revit models. It should be as easy as use same or similar activity definitions and replace the appbundle with your complicated workflows. 

