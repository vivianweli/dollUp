# dollUp
[Watch the demo video](https://youtu.be/U-Nba1odUlA)
![image](https://github.com/user-attachments/assets/2e01791b-28f4-42df-a398-5442e19c9e4f)
Doll Up is an interactive AR game that combines physical markers and digital menus to create a playful and immersive doll-dressing experience. Players can scan physical objects, including a doll marker, two cultural-themed scene markers, and a six-sided cubed marker, to display scenes and style a virtual doll model in real-time. By interacting with both the physical cube and the digital interface, players can explore various skins, outfits, and hairstyles, set their scene in iconic locations, and capture their designs.



## Real-time AR
1. One doll marker: displays the base virtual doll model and activates the virtual menu. At initialization, the doll is only dressed with undergarments.
2. Two cultured-themed scene markers: displays iconic buildings and art features according to the culture indicated by the marker
   - Chinese Traditional: Classic architecture and stone lion
   - Parisian Style: Eiffel tower, Parisian police station, and romantic café
3. One 6-sided cubed marker: displays the clothing and color customization menu one at a time according to the side detected. There is a different menu for tops, pants, shoes and hairstyle between the Chinese scene and the Parisian scene.
   - Tops: 3 styles including tank tops, t-shirts, long-sleeved shirts
    - Pants: 2 styles including tights and sport pants
    -Shoes: 3 styles of sneakers in various colors
    - Hairstyle: 3 styles including bob-cut, long-hair, ponytails, etc
    - Skin Color: Caucasian, Asian, African
    - Hair Color: Blonde, Black, Brown
      
## Interaction with Physical Objects
In our system, physical interaction plays a key role in creating an immersive and intuitive experience. We use a six-sided cube to control the menu appearance of available costumes and colors. By rotating the cube to scan a specific side of the cube, players can seamlessly navigate through a variety of menu options assigned to each cube side, including tops, pants, shoes, hairstyle, skin color, and hair color.

The interaction between the cultured-themed scene marker and the cubed marker is important. Since the customization menus for tops, pants, shoes and hairstyles are different for each of the two cultural styles, only if both markers are present will these menus be activated. Skin color and hair color menus can be displayed successfully even if the scene marker is absent.

## Interaction with Virtual Objects
The virtual menu includes all the additional extensions and the clothing/color customization menu. The additional extensions menu appears if the doll marker is present, while the clothing/color customization menu only appears if the six-sided cubed marker is also present.

If a clothing/color customization menu item has not been opened before, only the menu title appears. If the menu is activated (when a scene marker is present), by clicking on the menu title, a selection panel that displays the corresponding style/color options opens up at the bottom of the screen. Items/colors are displayed in an intuitive, horizontal layout, with image previews so players can easily predict the outcomes of their selection. By simply pressing on any item/color image in the selection panel, the virtual doll can instantly try on the selected style.

## Additional Extensions (Virtual Objects In the Menu)
The virtual menu also includes a button to switch expressions, enriching the virtual doll's customization. Players can click this button to select between 5 different expressions that best suit their doll's personality or mood including a neutral, smiley, angry, puzzled, and pouty face. This feature adds a layer of expressiveness and personalization to the overall experience, making the interaction fun and engaging.

A screenshot function is also conveniently added, allowing players to capture and share an image of their customized doll with the surrounding scene. The screenshot function does not capture the menu, but only captures the doll in its current outfit, chosen expression, and the themed scene for added context. This feature makes it easy for players to share and showcase their styled dolls to friends and family which encourages social interaction and engagement, turning each customization into a shareable moment.

A zoom in and a zoom out button are added to enhance overall user experience. The zoom in button enables players to scale up the virtual doll, offering a closed-up view during detailed customization and styling. The zoom out button resets the doll size back to the original setting for a full perspective of the scene with the doll, and is useful when taking a screenshot.

## Images Attribution ##
All images are obtained from Freepik.
- Doll Marker - <a href="https://www.freepik.com/free-vector/set-cute-girl-cartoon-character_47757883.htm#fromView=search&page=1&position=12&uuid=e95c0ed4-a966-450b-aaec-c5f6845900ca">Icon by brgfx</a>
- Parisian Scene Marker - <a href="https://fr.freepik.com/vecteurs-libre/ensemble-elements-paris-aquarelle_950775.htm#fromView=author&page=1&position=4&uuid=9fb94c94-be40-4b5a-9466-954e05d8a45a&new_detail=true">Icon by Freepik</a>
- Chinese Scene Marker - <a href="https://fr.freepik.com/vecteurs-libre/collection-elements-design-plats-pour-festival-du-nouvel-an-chinois_93759519.htm#fromView=search&page=1&position=14&uuid=4d3cf355-ea3c-41a9-9090-1b7b1df7f529">Icon by Freepik</a>
- Tops Marker - <a href="https://www.freepik.com/free-vector/t-shirts-collection-different-colors_2415577.htm#fromView=image_search_similar&page=1&position=0&uuid=e3355e47-9719-4ccc-ad3f-2a715fcdb032">Icon by Freepik</a>
- Pants Marker - <a href="https://www.freepik.com/free-vector/summer-fashion-yellow-blue-floral-shorts_137411643.htm#fromView=search&page=1&position=22&uuid=accdc08b-c60a-4d4d-978c-71c9a64c537f">Icon by gstudioimagen</a>
- Shoes Marker - <a href="https://www.freepik.com/free-vector/footwear-colored-icons-set_4431156.htm#fromView=search&page=1&position=0&uuid=765fde9a-b2a8-4456-975f-b7a82b4ebea0">Icon by macrovector_official</a>
- Hairstyle Marker - <a href="https://www.freepik.com/free-vector/hand-drawn-curly-hair-types-with-women_12428982.htm#fromView=search&page=1&position=4&uuid=2457b67b-aba8-4205-a627-efc8c891a784">Icon by Freepik</a>
- Hair Color Marker - <a href="https://www.freepik.com/free-vector/coloring-your-hair-doodle-sticker-vector_34381472.htm#fromView=search&page=1&position=30&uuid=1bb8fa11-04c2-4551-a239-9718dd2ed3e3">Icon by rawpixel.com</a>
- Skin Color Marker - <a href="https://www.freepik.com/free-vector/international-group-women-with-flat-design_3290713.htm#fromView=search&page=1&position=37&uuid=167c8860-a25f-402a-b749-133bab97c68c">Icon by Freepik</a>
