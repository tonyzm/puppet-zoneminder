puppet-zoneminder
=================

## Overview

A puppet module to completely install ZoneMinder 1.25.0 from source, including mastertheknife's patch and a WebUI with apache.

## Platforms
 * Ubuntu 12.04

## Issues
 * Should I install ffmpeg from source, or from the package repo?  Does the repo version of ffmpeg even work?
 * Need to add checks for Ubuntu.  This will probably fail misserably on ! Ubuntu
 * Should I use fastcgi and nginx?
 * I should move the different install sections to subclasses (what are they called again?)
 * I should move the libjpeg deb to module, so it doesn't rely on a mirror
