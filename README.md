# Instructions
1. Clone repo & update corneish_zen.keymap (refer to [ZMK docs](https://zmk.dev/docs))
2. Optionally, configure corneish_zen.conf and others
3. Commit and push changes, which will trigger GH Actions
4. Once Actions completes its build, view the Workflow tied to your changes, and download the `firmware.zip` located under "Artifacts"
5. Extract the two `.uf2` files found in the zip
6. Plug in one of the Corne-ish Zen halves and double tap the reset button on the top to enter bootloader mode. A folder/disk should pop up with the contents of that half.
7. Drag and drop the _correct_ `.uf2` file without touching any of the existing files in that keyboard
8. The keyboard should automatically close and eject upon successful upload
9. Repeat the upload for the other half

### Links
[Official LOWPROKB GH](https://github.com/LOWPROKB/zmk-config-Corne-ish-Zen)
[Official Corne-ish Zen support page](https://lowprokb.ca/pages/corne-ish-zen-support)
[PDF of keyboard's physical layout](https://cdn.shopify.com/s/files/1/0523/0847/6068/files/Corne-sih_Zen_physical_layout.pdf?v=1628978254)
[PDF of keyboard screen iconography](https://cdn.shopify.com/s/files/1/0523/0847/6068/files/Corne-ish_Zen_Display_Iconography.pdf?v=1628984746)
[Additional improvements courtesy of caksoylar](https://gist.github.com/caksoylar/c411313990978e1903c244f03039187a)