# WWIVNet
***

## What's a WWIVNet?
WWIVNet refers to a WWIV BBS based Net that uses WWIV's message and network 
packet system to share email and sub messages. There are and have been other 
WWIVNet based networks, similiar to how there are more than one FidoNet 
Technology based net. All of these nets are covered on the [Other Nets](othernets) page.

For the purpose of this page, WWIVNet refers to the specific instance of a 
WWIVNet that is the primary network for WWIV BBSes called WWIVNet.

## Technical Overview of WWIVNet

On November 2, 2015, WWIVNet switched to [BINKP](https://en.wikipedia.org/wiki/Binkp) as the underlying protocol for transferring net email and sub messages. The design of the network currently is a hub and spoke model with one node "@1" at the center point for all traffic flow.

## Joining WWIVNet

Thanks for your interest in WWIVnet,
all you need to join is a WWIV bbs heres the application below.

## WWIVnet Application for Membership

WWIVnet is a mail network for WWIV, and compatible bulletin board
systems. If you would like to join, please fill out this application.
When you've completed it, you must rename it to <last_name>.APP. This is
to prevent it from being looked over or overwritten by another application.

The best way to have your application processed is to get on a WWIVnet
BBS and mail this completed application to either the WWIVnet Network 
Coordinator, Weatherman 1@1 WWIVnet or email mark@weather-station.org


    =============================================================================
       WWIV Network Application for Membership
    -----------------------------------------------------------------------------
    SYSTEM OPERATOR INFORMATION:
        Real Full Name    :
        Your Handle/Alias :
        Home Phone Number : 
        Best Hours to Call: 
        Street/Mailing Address: 
        City: 
        State:      Zip Code:
    
    BBS INFORMATION:
        Bulletin Board Name:
        Bulletin Board Phone or Telnet Address:
        Hours of operation: 
        Months the BBS has been up: 
        WWIV Software Version:               
        Reg Number (if you have one): 
        Other networks you carry:

    Signature/Name:                              Date:
    
## [Configuring WWIVNet on Windows](wwivnetwin)
## [Configuring WWIVNet on Linux](wwivnetlinux)
## Maintaining your WWIVNet Connections
When you setup WWIVNet you download WWIVNET-##.zip from the build server and put the files in ```\wwiv\nets\wwivnet```. Occasionally you need to update these files so your BBS knowns who the new nodes & SUBs are on the net as well as which ones have gone away. If you are NOT also setup to get a Usenet feed you can copy the new files from the zip to ```\wwiv\net\wwivnet``` each time they are updated.

If you are also getting a feed from Usenet you have customized these files and you need to maintain your edits. These are the files you need to edit each time you get a new set of WWIVNet files.

**TODO** This in progress. See [Issue 229](https://github.com/wwivbbs/wwiv/issues/229).  

## Hosting your own WWIVNet SUB

If\when you are are ready to host your own WWIVNet sub here are the steps to take:

* Set up your sub locally in your BBS first. This is harmless.
* Get to the Sub Editor in //SYSOP, from the menu with //BE or "B" from the WFC screen.
* Choose to Insert a new SUB and fill-out the Name, and Filename fields at a minimum.
* Then choose "J" Net Info and select WWIVNet
* The SUBTYPE is the internal name of the sub in WWIVNet this must be unique (see SUBS.LST)
* Select YES you will be hosting the SUB.
* It is easiest and best to also allow auto add/drop requests. Unless your Sub is more exclusive.
* Select YES to add it to SUBS.LST to make it public.  
**Note:** Currently we have to manually share the subs.lst, that will be fixed in the future.
* Add your Sub to the subs.lst or request help on the WWIV Sysops Sub
* Post an announcement on the WWIVNet Sub Yellow Pages to advertise your new sub

***
Within the Net37.zip there are two documents and I've also posted them on the wiki. They have a lot of technical information if you'd like to read it.

* [NET37.DOC](net37doc) <- Has all the installation information (Must Read!)
* [NET37TEC.DOC](net37tecdoc) <- Good technical read on the inner workings of WWIVNet (optional)