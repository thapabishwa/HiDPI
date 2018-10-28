HiDPI fix for Awesome WM [Arch-Linux-MBP11.x]
===

Introduction
------
HiDPI (High Dots Per Inch) displays, also known by Apple's "Retina Display" marketing name, are screens with a high resolution in a relatively small format. They are mostly found in high-end laptops and monitors.
Not all software behaves well in high-resolution mode yet.
<br><br>

This repo consists xinit and Awesome WM theme files to provide a HiDPI fix for the Retina MacBook running on Arch.<br>

Dependencies
------

1. Firefox <br>
2. xdg-desktop-menu<br>
3. alsa-utils<br>
4. curl<br>
5. imagemagick<br>
6. Ubuntu TTF Fonts<br>
7. xbacklight<br>

Installation
------

Run the following command to download this project using [Git](http://git-scm.com).

  - git clone https://github.com/thapabishwa/HiDPI.git
  - cd HiDPI
  - cp .X* ~/.
  - cp .x* ~/.
  - mkdir ~/.config/awesome
  - mv awesome-copycats-mbp awesome
  - cp -R awesome ~/.config/

Contributing
------------

1. [Fork](https://github.com/thapabishwa/HiDPI.git/fork) HiDPI
2. Create a topic branch - `git checkout -b my_branch`
3. Push to your branch - `git push origin my_branch`
4. Create a [Pull Request] from your branch
5. That's it!

License
------

See LICENSE.md.

Disclaimer
------

The copyright holders are not liable for any damage(s) incurred due to improper use.

Contact
------

Shoot me an [email](mailto:thapabishwa@aol.com?subject=hidpi-arch-linux-mbp) if you have any questions.
