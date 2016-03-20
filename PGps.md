# Introduction #
<p>GPS Tool for the Asteroid.</p>
<p>Note: this is a simple App for your car - no fancy UI, no editing. It's a Car Radio App and not a Smartphone App. </p>
<h1>Installation</h1>
<ul>
<li>Copy the content of the ZIP file to the SD Card of your Parrots Asteroid. </li>
<li>Edit configuration in /PGps </li>
</ul>

<h2>POI.txt</h2>
POI contains your points of interest. They will be shown on the "distance to POI" screen. The format is:
```
Vienna: 48.208402,16.373835
Berlin: 52.5016,13.4023
```

<h1>Features</h1>
<h2>Common</h2>
<p>
The main screen shows the current satellite status, current accuracy and current speed.<br>
If there is no GPS fix "no fix" will be shown. (this can be changed in the settings screen).<br>
</p>
<p>
You can change the screens by using the wheel.<br>
</p>
<h2>Distance to points of interest</h2>
<p>
This screen show the distance to a point of interest, saved in the file located on your SD-Card in /PGps/POI.txt.<br>
This is just the air line!<br>
</p>
<p>
A new POI can be saved by pressing the center button.<br>
</p>
<h2>Lat/Lon</h2>
This screen shows the current latitude and longitude.
<h2>Distance</h2>
<p>
This screen shows the current driven distance. The distance will be updated when the new location is more away then the current accuracy.<br>
</p>
<p>
The current distance can be reseted with the center button. This has no effect to the current tip log, if enabled.<br>
</p>
<h2>Current altitude</h2>
This screen shows the current altitude.
<h2>Trip logging</h2>
<p>
Trip logging can be enabled in the preferences. The default is enabled. A trip starts when the first GPS location has been captured and stopped when the radio is turned off.<br>
</p>
<p>
If you have a network connection the addressed of the starting point and ending point can be queried automatically. If you don't have network connection disable this feature to save your time.<br>
</p>
<p>
In the menu there is a "Show trips" entry. This will list all logged trips. In this screen, there is a "Export trips" menu item where you can export you trips to your SD-Card in /PGps.<br>
</p>
<p>
The merge trips settings will merge trips, where the pause is less then the given value. Trips shorter than 1 km will be deleted automatically.<br>
</p>

<h1>License</h1>
<p>GNU GPL v3<br>
<ul><li><a href='http://www.gnu.org/licenses/gpl.html'><a href='http://www.gnu.org/licenses/gpl.html'>http://www.gnu.org/licenses/gpl.html</a></a> </li>
</ul>
</p>

<h2>Parrots Copyright for the geo coder lib</h2>
```
 *
 * Copyright (c) 2011, Parrot
 * All rights reserved.
 *
 * Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
 *
 *   * Redistributions of source code must retain the above copyright notice,
 *     this list of conditions and the following disclaimer.
 *
 *   * Redistributions in binary form must reproduce the above copyright
 *     notice, this list of conditions and the following disclaimer in the
 *     documentation and/or other materials provided with the distribution.
 *
 *   * Neither the name of "Parrot SA" nor the names of its
 *     contributors may be used to endorse or promote products derived from
 *     this software without specific prior written permission.
 *
 * THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
 * AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, 
 * THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR 
 * PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR 
 * CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, 
 * EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, 
 * PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR 
 * PROFITS; OR BUSINESS
 * INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
 *
```