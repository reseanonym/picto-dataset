# Pictogram Dataset for Anonymous Review

To maintain the double-blind review process, all personal identifiers and file metadata have been completely stripped.

## 📊 Dataset Specifications
* **Total Pictograms:** 330
* **Format:** .JPG
* **Directory Structure:** All pictograms are available in the `/data` folder.

## 🏷️ File Naming Convention
Each pictogram in this dataset follows a structured naming pattern:

```text
{concept}_{condition_map}_{ranking}.ext
```

Where each field represents:
* **concept**: The concept represented by the pictogram (e.g., Ajolote).
* **condition_map**: The conditioning map used to generate the pictogram (e.g., canny).
* **ranking**: The rank obtained by the pictogram in the survey conducted to select the best pictogram among three alternatives (where 1 represents the highest-voted option).

**Remark.** Filenames corresponding to tied pictograms generated with the same condition map include the suffix `_dup` (e.g., `Bread_canny_1_dup.jpg`).

## 🖼️ Full Dataset Gallery
Below is the complete collection of pictograms included in this dataset:

<table>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Ajolote_canny_1.jpg" width="160" alt="Ajolote_canny_1.jpg"><br>
      <code>Ajolote_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Ajolote_canny_2.jpg" width="160" alt="Ajolote_canny_2.jpg"><br>
      <code>Ajolote_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Ajolote_canny_3.jpg" width="160" alt="Ajolote_canny_3.jpg"><br>
      <code>Ajolote_canny_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Angry_depth_1.jpg" width="160" alt="Angry_depth_1.jpg"><br>
      <code>Angry_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Angry_depth_2.jpg" width="160" alt="Angry_depth_2.jpg"><br>
      <code>Angry_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Angry_seg_1.jpg" width="160" alt="Angry_seg_1.jpg"><br>
      <code>Angry_seg_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Baby_depth_1.jpg" width="160" alt="Baby_depth_1.jpg"><br>
      <code>Baby_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Baby_depth_2.jpg" width="160" alt="Baby_depth_2.jpg"><br>
      <code>Baby_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Baby_depth_3.jpg" width="160" alt="Baby_depth_3.jpg"><br>
      <code>Baby_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Bad_canny_2.jpg" width="160" alt="Bad_canny_2.jpg"><br>
      <code>Bad_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bad_canny_3.jpg" width="160" alt="Bad_canny_3.jpg"><br>
      <code>Bad_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bad_depth_1.jpg" width="160" alt="Bad_depth_1.jpg"><br>
      <code>Bad_depth_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Bed_canny_2.jpg" width="160" alt="Bed_canny_2.jpg"><br>
      <code>Bed_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bed_depth_3.jpg" width="160" alt="Bed_depth_3.jpg"><br>
      <code>Bed_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bed_hed_1.jpg" width="160" alt="Bed_hed_1.jpg"><br>
      <code>Bed_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Book_canny_2.jpg" width="160" alt="Book_canny_2.jpg"><br>
      <code>Book_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Book_canny_3.jpg" width="160" alt="Book_canny_3.jpg"><br>
      <code>Book_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Book_depth_1.jpg" width="160" alt="Book_depth_1.jpg"><br>
      <code>Book_depth_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Bored_canny_1.jpg" width="160" alt="Bored_canny_1.jpg"><br>
      <code>Bored_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bored_depth_2.jpg" width="160" alt="Bored_depth_2.jpg"><br>
      <code>Bored_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bored_depth_3.jpg" width="160" alt="Bored_depth_3.jpg"><br>
      <code>Bored_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Bread_canny_1.jpg" width="160" alt="Bread_canny_1.jpg"><br>
      <code>Bread_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bread_canny_1_dup.jpg" width="160" alt="Bread_canny_1_dup.jpg"><br>
      <code>Bread_canny_1_dup.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bread_depth_1.jpg" width="160" alt="Bread_depth_1.jpg"><br>
      <code>Bread_depth_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Brother_openpose_1.jpg" width="160" alt="Brother_openpose_1.jpg"><br>
      <code>Brother_openpose_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Brother_seg_2.jpg" width="160" alt="Brother_seg_2.jpg"><br>
      <code>Brother_seg_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Brother_seg_3.jpg" width="160" alt="Brother_seg_3.jpg"><br>
      <code>Brother_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Brush_teeth_canny_2.jpg" width="160" alt="Brush_teeth_canny_2.jpg"><br>
      <code>Brush_teeth_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Brush_teeth_depth_3.jpg" width="160" alt="Brush_teeth_depth_3.jpg"><br>
      <code>Brush_teeth_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Brush_teeth_hed_1.jpg" width="160" alt="Brush_teeth_hed_1.jpg"><br>
      <code>Brush_teeth_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Bus_canny_2.jpg" width="160" alt="Bus_canny_2.jpg"><br>
      <code>Bus_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bus_hed_1.jpg" width="160" alt="Bus_hed_1.jpg"><br>
      <code>Bus_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Bus_hed_3.jpg" width="160" alt="Bus_hed_3.jpg"><br>
      <code>Bus_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Calm_canny_2.jpg" width="160" alt="Calm_canny_2.jpg"><br>
      <code>Calm_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Calm_canny_3.jpg" width="160" alt="Calm_canny_3.jpg"><br>
      <code>Calm_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Calm_depth_1.jpg" width="160" alt="Calm_depth_1.jpg"><br>
      <code>Calm_depth_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Car_canny_1.jpg" width="160" alt="Car_canny_1.jpg"><br>
      <code>Car_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Car_depth_1.jpg" width="160" alt="Car_depth_1.jpg"><br>
      <code>Car_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Car_seg_2.jpg" width="160" alt="Car_seg_2.jpg"><br>
      <code>Car_seg_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Chair_canny_1.jpg" width="160" alt="Chair_canny_1.jpg"><br>
      <code>Chair_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Chair_depth_1.jpg" width="160" alt="Chair_depth_1.jpg"><br>
      <code>Chair_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Chair_hed_2.jpg" width="160" alt="Chair_hed_2.jpg"><br>
      <code>Chair_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Champurrado_canny_1.jpg" width="160" alt="Champurrado_canny_1.jpg"><br>
      <code>Champurrado_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Champurrado_depth_2.jpg" width="160" alt="Champurrado_depth_2.jpg"><br>
      <code>Champurrado_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Champurrado_hed_3.jpg" width="160" alt="Champurrado_hed_3.jpg"><br>
      <code>Champurrado_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Chichen_itza_canny_1.jpg" width="160" alt="Chichen_itza_canny_1.jpg"><br>
      <code>Chichen_itza_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Chichen_itza_canny_2.jpg" width="160" alt="Chichen_itza_canny_2.jpg"><br>
      <code>Chichen_itza_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Chichen_itza_depth_1.jpg" width="160" alt="Chichen_itza_depth_1.jpg"><br>
      <code>Chichen_itza_depth_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Close_depth_1.jpg" width="160" alt="Close_depth_1.jpg"><br>
      <code>Close_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Close_depth_2.jpg" width="160" alt="Close_depth_2.jpg"><br>
      <code>Close_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Close_depth_2_dup.jpg" width="160" alt="Close_depth_2_dup.jpg"><br>
      <code>Close_depth_2_dup.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Clothes_depth_3.jpg" width="160" alt="Clothes_depth_3.jpg"><br>
      <code>Clothes_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Clothes_seg_1.jpg" width="160" alt="Clothes_seg_1.jpg"><br>
      <code>Clothes_seg_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Clothes_seg_2.jpg" width="160" alt="Clothes_seg_2.jpg"><br>
      <code>Clothes_seg_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Come_depth_1.jpg" width="160" alt="Come_depth_1.jpg"><br>
      <code>Come_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Come_depth_2.jpg" width="160" alt="Come_depth_2.jpg"><br>
      <code>Come_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Come_hed_2.jpg" width="160" alt="Come_hed_2.jpg"><br>
      <code>Come_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Dia_de_muertos_canny_1.jpg" width="160" alt="Dia_de_muertos_canny_1.jpg"><br>
      <code>Dia_de_muertos_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Dia_de_muertos_canny_2.jpg" width="160" alt="Dia_de_muertos_canny_2.jpg"><br>
      <code>Dia_de_muertos_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Dia_de_muertos_depth_3.jpg" width="160" alt="Dia_de_muertos_depth_3.jpg"><br>
      <code>Dia_de_muertos_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Doctor_canny_1.jpg" width="160" alt="Doctor_canny_1.jpg"><br>
      <code>Doctor_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Doctor_depth_2.jpg" width="160" alt="Doctor_depth_2.jpg"><br>
      <code>Doctor_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Doctor_depth_3.jpg" width="160" alt="Doctor_depth_3.jpg"><br>
      <code>Doctor_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Draw_canny_1.jpg" width="160" alt="Draw_canny_1.jpg"><br>
      <code>Draw_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Draw_canny_2.jpg" width="160" alt="Draw_canny_2.jpg"><br>
      <code>Draw_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Draw_hed_1.jpg" width="160" alt="Draw_hed_1.jpg"><br>
      <code>Draw_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Drink_depth_1.jpg" width="160" alt="Drink_depth_1.jpg"><br>
      <code>Drink_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Drink_depth_3.jpg" width="160" alt="Drink_depth_3.jpg"><br>
      <code>Drink_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Drink_hed_2.jpg" width="160" alt="Drink_hed_2.jpg"><br>
      <code>Drink_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Eat_canny_3.jpg" width="160" alt="Eat_canny_3.jpg"><br>
      <code>Eat_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Eat_hed_1.jpg" width="160" alt="Eat_hed_1.jpg"><br>
      <code>Eat_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Eat_hed_2.jpg" width="160" alt="Eat_hed_2.jpg"><br>
      <code>Eat_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Egg_canny_3.jpg" width="160" alt="Egg_canny_3.jpg"><br>
      <code>Egg_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Egg_depth_1.jpg" width="160" alt="Egg_depth_1.jpg"><br>
      <code>Egg_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Egg_depth_2.jpg" width="160" alt="Egg_depth_2.jpg"><br>
      <code>Egg_depth_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Excited_canny_3.jpg" width="160" alt="Excited_canny_3.jpg"><br>
      <code>Excited_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Excited_depth_1.jpg" width="160" alt="Excited_depth_1.jpg"><br>
      <code>Excited_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Excited_hed_2.jpg" width="160" alt="Excited_hed_2.jpg"><br>
      <code>Excited_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Excuse_me_canny_1.jpg" width="160" alt="Excuse_me_canny_1.jpg"><br>
      <code>Excuse_me_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Excuse_me_depth_1.jpg" width="160" alt="Excuse_me_depth_1.jpg"><br>
      <code>Excuse_me_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Excuse_me_depth_1_dup.jpg" width="160" alt="Excuse_me_depth_1_dup.jpg"><br>
      <code>Excuse_me_depth_1_dup.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Family_depth_2.jpg" width="160" alt="Family_depth_2.jpg"><br>
      <code>Family_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Family_depth_3.jpg" width="160" alt="Family_depth_3.jpg"><br>
      <code>Family_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Family_openpose_1.jpg" width="160" alt="Family_openpose_1.jpg"><br>
      <code>Family_openpose_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Father_depth_1.jpg" width="160" alt="Father_depth_1.jpg"><br>
      <code>Father_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Father_depth_2.jpg" width="160" alt="Father_depth_2.jpg"><br>
      <code>Father_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Father_depth_2_dup.jpg" width="160" alt="Father_depth_2_dup.jpg"><br>
      <code>Father_depth_2_dup.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Finish_depth_2.jpg" width="160" alt="Finish_depth_2.jpg"><br>
      <code>Finish_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Finish_depth_3.jpg" width="160" alt="Finish_depth_3.jpg"><br>
      <code>Finish_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Finish_seg_1.jpg" width="160" alt="Finish_seg_1.jpg"><br>
      <code>Finish_seg_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Fish_depth_3.jpg" width="160" alt="Fish_depth_3.jpg"><br>
      <code>Fish_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Fish_seg_1.jpg" width="160" alt="Fish_seg_1.jpg"><br>
      <code>Fish_seg_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Fish_seg_2.jpg" width="160" alt="Fish_seg_2.jpg"><br>
      <code>Fish_seg_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Frida_depth_1.jpg" width="160" alt="Frida_depth_1.jpg"><br>
      <code>Frida_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Frida_depth_2.jpg" width="160" alt="Frida_depth_2.jpg"><br>
      <code>Frida_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Frida_depth_3.jpg" width="160" alt="Frida_depth_3.jpg"><br>
      <code>Frida_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Friend_depth_1.jpg" width="160" alt="Friend_depth_1.jpg"><br>
      <code>Friend_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Friend_openpose_2.jpg" width="160" alt="Friend_openpose_2.jpg"><br>
      <code>Friend_openpose_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Friend_openpose_3.jpg" width="160" alt="Friend_openpose_3.jpg"><br>
      <code>Friend_openpose_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Fruit_depth_1.jpg" width="160" alt="Fruit_depth_1.jpg"><br>
      <code>Fruit_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Fruit_depth_2.jpg" width="160" alt="Fruit_depth_2.jpg"><br>
      <code>Fruit_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Fruit_depth_3.jpg" width="160" alt="Fruit_depth_3.jpg"><br>
      <code>Fruit_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Give_canny_2.jpg" width="160" alt="Give_canny_2.jpg"><br>
      <code>Give_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Give_depth_1.jpg" width="160" alt="Give_depth_1.jpg"><br>
      <code>Give_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Give_depth_2.jpg" width="160" alt="Give_depth_2.jpg"><br>
      <code>Give_depth_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Go_canny_1.jpg" width="160" alt="Go_canny_1.jpg"><br>
      <code>Go_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Go_depth_2.jpg" width="160" alt="Go_depth_2.jpg"><br>
      <code>Go_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Go_hed_3.jpg" width="160" alt="Go_hed_3.jpg"><br>
      <code>Go_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Good_canny_2.jpg" width="160" alt="Good_canny_2.jpg"><br>
      <code>Good_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Good_seg_1.jpg" width="160" alt="Good_seg_1.jpg"><br>
      <code>Good_seg_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Good_seg_3.jpg" width="160" alt="Good_seg_3.jpg"><br>
      <code>Good_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Goodbye_openpose_1.jpg" width="160" alt="Goodbye_openpose_1.jpg"><br>
      <code>Goodbye_openpose_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Goodbye_openpose_2.jpg" width="160" alt="Goodbye_openpose_2.jpg"><br>
      <code>Goodbye_openpose_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Goodbye_openpose_3.jpg" width="160" alt="Goodbye_openpose_3.jpg"><br>
      <code>Goodbye_openpose_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Grandfather_seg_1.jpg" width="160" alt="Grandfather_seg_1.jpg"><br>
      <code>Grandfather_seg_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Grandfather_seg_2.jpg" width="160" alt="Grandfather_seg_2.jpg"><br>
      <code>Grandfather_seg_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Grandfather_seg_3.jpg" width="160" alt="Grandfather_seg_3.jpg"><br>
      <code>Grandfather_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Grandmother_depth_1.jpg" width="160" alt="Grandmother_depth_1.jpg"><br>
      <code>Grandmother_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Grandmother_hed_2.jpg" width="160" alt="Grandmother_hed_2.jpg"><br>
      <code>Grandmother_hed_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Grandmother_seg_3.jpg" width="160" alt="Grandmother_seg_3.jpg"><br>
      <code>Grandmother_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Happy_canny_1.jpg" width="160" alt="Happy_canny_1.jpg"><br>
      <code>Happy_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Happy_depth_2.jpg" width="160" alt="Happy_depth_2.jpg"><br>
      <code>Happy_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Happy_openpose_3.jpg" width="160" alt="Happy_openpose_3.jpg"><br>
      <code>Happy_openpose_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Hello_depth_2.jpg" width="160" alt="Hello_depth_2.jpg"><br>
      <code>Hello_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Hello_seg_1.jpg" width="160" alt="Hello_seg_1.jpg"><br>
      <code>Hello_seg_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Hello_seg_1_dup1.jpg" width="160" alt="Hello_seg_1_dup1.jpg"><br>
      <code>Hello_seg_1_dup1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Help_openpose_1.jpg" width="160" alt="Help_openpose_1.jpg"><br>
      <code>Help_openpose_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Help_openpose_2.jpg" width="160" alt="Help_openpose_2.jpg"><br>
      <code>Help_openpose_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Help_openpose_3.jpg" width="160" alt="Help_openpose_3.jpg"><br>
      <code>Help_openpose_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Hospital_depth_1.jpg" width="160" alt="Hospital_depth_1.jpg"><br>
      <code>Hospital_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Hospital_hed_1.jpg" width="160" alt="Hospital_hed_1.jpg"><br>
      <code>Hospital_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Hospital_hed_2.jpg" width="160" alt="Hospital_hed_2.jpg"><br>
      <code>Hospital_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/House_depth_1.jpg" width="160" alt="House_depth_1.jpg"><br>
      <code>House_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/House_hed_1.jpg" width="160" alt="House_hed_1.jpg"><br>
      <code>House_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/House_hed_2.jpg" width="160" alt="House_hed_2.jpg"><br>
      <code>House_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Hungry_canny_1.jpg" width="160" alt="Hungry_canny_1.jpg"><br>
      <code>Hungry_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Hungry_canny_2.jpg" width="160" alt="Hungry_canny_2.jpg"><br>
      <code>Hungry_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Hungry_canny_3.jpg" width="160" alt="Hungry_canny_3.jpg"><br>
      <code>Hungry_canny_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Juice_depth_1.jpg" width="160" alt="Juice_depth_1.jpg"><br>
      <code>Juice_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Juice_depth_1_dup.jpg" width="160" alt="Juice_depth_1_dup.jpg"><br>
      <code>Juice_depth_1_dup.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Juice_depth_2.jpg" width="160" alt="Juice_depth_2.jpg"><br>
      <code>Juice_depth_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Jump_depth_1.jpg" width="160" alt="Jump_depth_1.jpg"><br>
      <code>Jump_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Jump_seg_2.jpg" width="160" alt="Jump_seg_2.jpg"><br>
      <code>Jump_seg_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Jump_seg_3.jpg" width="160" alt="Jump_seg_3.jpg"><br>
      <code>Jump_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Later_hed_1.jpg" width="160" alt="Later_hed_1.jpg"><br>
      <code>Later_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Later_hed_2.jpg" width="160" alt="Later_hed_2.jpg"><br>
      <code>Later_hed_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Later_hed_3.jpg" width="160" alt="Later_hed_3.jpg"><br>
      <code>Later_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Listen_depth_2.jpg" width="160" alt="Listen_depth_2.jpg"><br>
      <code>Listen_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Listen_hed_1.jpg" width="160" alt="Listen_hed_1.jpg"><br>
      <code>Listen_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Listen_seg_3.jpg" width="160" alt="Listen_seg_3.jpg"><br>
      <code>Listen_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Look_depth_1.jpg" width="160" alt="Look_depth_1.jpg"><br>
      <code>Look_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Look_hed_2_dup1.jpg" width="160" alt="Look_hed_2_dup1.jpg"><br>
      <code>Look_hed_2_dup1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Look_hed_3.jpg" width="160" alt="Look_hed_3.jpg"><br>
      <code>Look_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Love_depth_1.jpg" width="160" alt="Love_depth_1.jpg"><br>
      <code>Love_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Love_depth_2.jpg" width="160" alt="Love_depth_2.jpg"><br>
      <code>Love_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Love_depth_3.jpg" width="160" alt="Love_depth_3.jpg"><br>
      <code>Love_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Mariachi_depth_2.jpg" width="160" alt="Mariachi_depth_2.jpg"><br>
      <code>Mariachi_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Mariachi_depth_3.jpg" width="160" alt="Mariachi_depth_3.jpg"><br>
      <code>Mariachi_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Mariachi_hed_1.jpg" width="160" alt="Mariachi_hed_1.jpg"><br>
      <code>Mariachi_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Me_canny_3.jpg" width="160" alt="Me_canny_3.jpg"><br>
      <code>Me_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Me_depth_2.jpg" width="160" alt="Me_depth_2.jpg"><br>
      <code>Me_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Me_hed_1.jpg" width="160" alt="Me_hed_1.jpg"><br>
      <code>Me_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Meat_depth_3.jpg" width="160" alt="Meat_depth_3.jpg"><br>
      <code>Meat_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Meat_seg_1.jpg" width="160" alt="Meat_seg_1.jpg"><br>
      <code>Meat_seg_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Meat_seg_2.jpg" width="160" alt="Meat_seg_2.jpg"><br>
      <code>Meat_seg_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Medicine_depth_3.jpg" width="160" alt="Medicine_depth_3.jpg"><br>
      <code>Medicine_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Medicine_hed_1.jpg" width="160" alt="Medicine_hed_1.jpg"><br>
      <code>Medicine_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Medicine_hed_2.jpg" width="160" alt="Medicine_hed_2.jpg"><br>
      <code>Medicine_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Milk_canny_3.jpg" width="160" alt="Milk_canny_3.jpg"><br>
      <code>Milk_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Milk_hed_2.jpg" width="160" alt="Milk_hed_2.jpg"><br>
      <code>Milk_hed_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Milk_seg_1.jpg" width="160" alt="Milk_seg_1.jpg"><br>
      <code>Milk_seg_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/More_canny_2.jpg" width="160" alt="More_canny_2.jpg"><br>
      <code>More_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/More_canny_2_dup.jpg" width="160" alt="More_canny_2_dup.jpg"><br>
      <code>More_canny_2_dup.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/More_seg_1.jpg" width="160" alt="More_seg_1.jpg"><br>
      <code>More_seg_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Mother_depth_3.jpg" width="160" alt="Mother_depth_3.jpg"><br>
      <code>Mother_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Mother_hed_1.jpg" width="160" alt="Mother_hed_1.jpg"><br>
      <code>Mother_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Mother_hed_2.jpg" width="160" alt="Mother_hed_2.jpg"><br>
      <code>Mother_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/No_canny_3.jpg" width="160" alt="No_canny_3.jpg"><br>
      <code>No_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/No_depth_1.jpg" width="160" alt="No_depth_1.jpg"><br>
      <code>No_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/No_hed_2.jpg" width="160" alt="No_hed_2.jpg"><br>
      <code>No_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Now_depth_1.jpg" width="160" alt="Now_depth_1.jpg"><br>
      <code>Now_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Now_depth_2.jpg" width="160" alt="Now_depth_2.jpg"><br>
      <code>Now_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Now_depth_3.jpg" width="160" alt="Now_depth_3.jpg"><br>
      <code>Now_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Open_canny_1.jpg" width="160" alt="Open_canny_1.jpg"><br>
      <code>Open_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Open_depth_2.jpg" width="160" alt="Open_depth_2.jpg"><br>
      <code>Open_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Open_hed_1.jpg" width="160" alt="Open_hed_1.jpg"><br>
      <code>Open_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Pain_depth_1.jpg" width="160" alt="Pain_depth_1.jpg"><br>
      <code>Pain_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Pain_depth_2.jpg" width="160" alt="Pain_depth_2.jpg"><br>
      <code>Pain_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Pain_depth_2_dup.jpg" width="160" alt="Pain_depth_2_dup.jpg"><br>
      <code>Pain_depth_2_dup.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Park_depth_2.jpg" width="160" alt="Park_depth_2.jpg"><br>
      <code>Park_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Park_seg_1.jpg" width="160" alt="Park_seg_1.jpg"><br>
      <code>Park_seg_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Park_seg_3.jpg" width="160" alt="Park_seg_3.jpg"><br>
      <code>Park_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/People_seg_1.jpg" width="160" alt="People_seg_1.jpg"><br>
      <code>People_seg_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/People_seg_2.jpg" width="160" alt="People_seg_2.jpg"><br>
      <code>People_seg_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/People_seg_3.jpg" width="160" alt="People_seg_3.jpg"><br>
      <code>People_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Phone_canny_3.jpg" width="160" alt="Phone_canny_3.jpg"><br>
      <code>Phone_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Phone_depth_1.jpg" width="160" alt="Phone_depth_1.jpg"><br>
      <code>Phone_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Phone_depth_2.jpg" width="160" alt="Phone_depth_2.jpg"><br>
      <code>Phone_depth_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Pinata_depth_2.jpg" width="160" alt="Pinata_depth_2.jpg"><br>
      <code>Pinata_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Pinata_depth_3.jpg" width="160" alt="Pinata_depth_3.jpg"><br>
      <code>Pinata_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Pinata_hed_1.jpg" width="160" alt="Pinata_hed_1.jpg"><br>
      <code>Pinata_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Play_canny_1.jpg" width="160" alt="Play_canny_1.jpg"><br>
      <code>Play_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Play_canny_2.jpg" width="160" alt="Play_canny_2.jpg"><br>
      <code>Play_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Play_canny_3.jpg" width="160" alt="Play_canny_3.jpg"><br>
      <code>Play_canny_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Playground_canny_1.jpg" width="160" alt="Playground_canny_1.jpg"><br>
      <code>Playground_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Playground_canny_2.jpg" width="160" alt="Playground_canny_2.jpg"><br>
      <code>Playground_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Playground_depth_3.jpg" width="160" alt="Playground_depth_3.jpg"><br>
      <code>Playground_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Please_depth_1.jpg" width="160" alt="Please_depth_1.jpg"><br>
      <code>Please_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Please_depth_2.jpg" width="160" alt="Please_depth_2.jpg"><br>
      <code>Please_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Please_depth_3.jpg" width="160" alt="Please_depth_3.jpg"><br>
      <code>Please_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Pozole_canny_1.jpg" width="160" alt="Pozole_canny_1.jpg"><br>
      <code>Pozole_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Pozole_canny_2.jpg" width="160" alt="Pozole_canny_2.jpg"><br>
      <code>Pozole_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Pozole_hed_1.jpg" width="160" alt="Pozole_hed_1.jpg"><br>
      <code>Pozole_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Rest_depth_1.jpg" width="160" alt="Rest_depth_1.jpg"><br>
      <code>Rest_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Rest_depth_2.jpg" width="160" alt="Rest_depth_2.jpg"><br>
      <code>Rest_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Rest_openpose_3.jpg" width="160" alt="Rest_openpose_3.jpg"><br>
      <code>Rest_openpose_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Restaurant_canny_2.jpg" width="160" alt="Restaurant_canny_2.jpg"><br>
      <code>Restaurant_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Restaurant_depth_1.jpg" width="160" alt="Restaurant_depth_1.jpg"><br>
      <code>Restaurant_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Restaurant_depth_2.jpg" width="160" alt="Restaurant_depth_2.jpg"><br>
      <code>Restaurant_depth_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Rice_canny_3.jpg" width="160" alt="Rice_canny_3.jpg"><br>
      <code>Rice_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Rice_depth_2.jpg" width="160" alt="Rice_depth_2.jpg"><br>
      <code>Rice_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Rice_hed_1.jpg" width="160" alt="Rice_hed_1.jpg"><br>
      <code>Rice_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Run_openpose_1.jpg" width="160" alt="Run_openpose_1.jpg"><br>
      <code>Run_openpose_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Run_openpose_2.jpg" width="160" alt="Run_openpose_2.jpg"><br>
      <code>Run_openpose_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Run_seg_1.jpg" width="160" alt="Run_seg_1.jpg"><br>
      <code>Run_seg_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Sad_depth_1.jpg" width="160" alt="Sad_depth_1.jpg"><br>
      <code>Sad_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Sad_hed_1.jpg" width="160" alt="Sad_hed_1.jpg"><br>
      <code>Sad_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Sad_openpose_1.jpg" width="160" alt="Sad_openpose_1.jpg"><br>
      <code>Sad_openpose_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Scared_depth_1.jpg" width="160" alt="Scared_depth_1.jpg"><br>
      <code>Scared_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Scared_depth_2.jpg" width="160" alt="Scared_depth_2.jpg"><br>
      <code>Scared_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Scared_depth_3.jpg" width="160" alt="Scared_depth_3.jpg"><br>
      <code>Scared_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/School_canny_1.jpg" width="160" alt="School_canny_1.jpg"><br>
      <code>School_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/School_depth_2.jpg" width="160" alt="School_depth_2.jpg"><br>
      <code>School_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/School_depth_3.jpg" width="160" alt="School_depth_3.jpg"><br>
      <code>School_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Shower_canny_1.jpg" width="160" alt="Shower_canny_1.jpg"><br>
      <code>Shower_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Shower_canny_2.jpg" width="160" alt="Shower_canny_2.jpg"><br>
      <code>Shower_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Shower_hed_3.jpg" width="160" alt="Shower_hed_3.jpg"><br>
      <code>Shower_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Sick_canny_1.jpg" width="160" alt="Sick_canny_1.jpg"><br>
      <code>Sick_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Sick_hed_2.jpg" width="160" alt="Sick_hed_2.jpg"><br>
      <code>Sick_hed_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Sick_hed_3.jpg" width="160" alt="Sick_hed_3.jpg"><br>
      <code>Sick_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Sister_depth_2.jpg" width="160" alt="Sister_depth_2.jpg"><br>
      <code>Sister_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Sister_openpose_1.jpg" width="160" alt="Sister_openpose_1.jpg"><br>
      <code>Sister_openpose_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Sister_openpose_3.jpg" width="160" alt="Sister_openpose_3.jpg"><br>
      <code>Sister_openpose_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Sleep_depth_1.jpg" width="160" alt="Sleep_depth_1.jpg"><br>
      <code>Sleep_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Sleep_depth_2.jpg" width="160" alt="Sleep_depth_2.jpg"><br>
      <code>Sleep_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Sleep_depth_3.jpg" width="160" alt="Sleep_depth_3.jpg"><br>
      <code>Sleep_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Soup_seg_1.jpg" width="160" alt="Soup_seg_1.jpg"><br>
      <code>Soup_seg_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Soup_seg_2.jpg" width="160" alt="Soup_seg_2.jpg"><br>
      <code>Soup_seg_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Soup_seg_3.jpg" width="160" alt="Soup_seg_3.jpg"><br>
      <code>Soup_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Stop_hed_1.jpg" width="160" alt="Stop_hed_1.jpg"><br>
      <code>Stop_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Stop_hed_2.jpg" width="160" alt="Stop_hed_2.jpg"><br>
      <code>Stop_hed_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Stop_hed_3.jpg" width="160" alt="Stop_hed_3.jpg"><br>
      <code>Stop_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Store_depth_3.jpg" width="160" alt="Store_depth_3.jpg"><br>
      <code>Store_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Store_hed_1.jpg" width="160" alt="Store_hed_1.jpg"><br>
      <code>Store_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Store_seg_2.jpg" width="160" alt="Store_seg_2.jpg"><br>
      <code>Store_seg_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Street_canny_1.jpg" width="160" alt="Street_canny_1.jpg"><br>
      <code>Street_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Street_seg_2.jpg" width="160" alt="Street_seg_2.jpg"><br>
      <code>Street_seg_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Street_seg_3.jpg" width="160" alt="Street_seg_3.jpg"><br>
      <code>Street_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Surprise_depth_1.jpg" width="160" alt="Surprise_depth_1.jpg"><br>
      <code>Surprise_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Surprise_seg_2.jpg" width="160" alt="Surprise_seg_2.jpg"><br>
      <code>Surprise_seg_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Surprise_seg_3.jpg" width="160" alt="Surprise_seg_3.jpg"><br>
      <code>Surprise_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Taco_depth_1.jpg" width="160" alt="Taco_depth_1.jpg"><br>
      <code>Taco_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Taco_depth_2.jpg" width="160" alt="Taco_depth_2.jpg"><br>
      <code>Taco_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Taco_depth_2_dup.jpg" width="160" alt="Taco_depth_2_dup.jpg"><br>
      <code>Taco_depth_2_dup.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Take_canny_3.jpg" width="160" alt="Take_canny_3.jpg"><br>
      <code>Take_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Take_depth_1.jpg" width="160" alt="Take_depth_1.jpg"><br>
      <code>Take_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Take_depth_2.jpg" width="160" alt="Take_depth_2.jpg"><br>
      <code>Take_depth_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Talk_canny_1.jpg" width="160" alt="Talk_canny_1.jpg"><br>
      <code>Talk_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Talk_depth_2.jpg" width="160" alt="Talk_depth_2.jpg"><br>
      <code>Talk_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Talk_seg_3.jpg" width="160" alt="Talk_seg_3.jpg"><br>
      <code>Talk_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Teacher_canny_3.jpg" width="160" alt="Teacher_canny_3.jpg"><br>
      <code>Teacher_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Teacher_depth_1.jpg" width="160" alt="Teacher_depth_1.jpg"><br>
      <code>Teacher_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Teacher_openpose_2.jpg" width="160" alt="Teacher_openpose_2.jpg"><br>
      <code>Teacher_openpose_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Tequila_canny_2.jpg" width="160" alt="Tequila_canny_2.jpg"><br>
      <code>Tequila_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Tequila_depth_1.jpg" width="160" alt="Tequila_depth_1.jpg"><br>
      <code>Tequila_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Tequila_hed_1.jpg" width="160" alt="Tequila_hed_1.jpg"><br>
      <code>Tequila_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Thank_you_depth_1.jpg" width="160" alt="Thank_you_depth_1.jpg"><br>
      <code>Thank_you_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Thank_you_depth_1_dup.jpg" width="160" alt="Thank_you_depth_1_dup.jpg"><br>
      <code>Thank_you_depth_1_dup.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Thank_you_hed_2.jpg" width="160" alt="Thank_you_hed_2.jpg"><br>
      <code>Thank_you_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Thirsty_hed_1.jpg" width="160" alt="Thirsty_hed_1.jpg"><br>
      <code>Thirsty_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Thirsty_hed_2.jpg" width="160" alt="Thirsty_hed_2.jpg"><br>
      <code>Thirsty_hed_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Thirsty_hed_3.jpg" width="160" alt="Thirsty_hed_3.jpg"><br>
      <code>Thirsty_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Tired_canny_3.jpg" width="160" alt="Tired_canny_3.jpg"><br>
      <code>Tired_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Tired_depth_2.jpg" width="160" alt="Tired_depth_2.jpg"><br>
      <code>Tired_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Tired_hed_1.jpg" width="160" alt="Tired_hed_1.jpg"><br>
      <code>Tired_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Toilet_depth_2.jpg" width="160" alt="Toilet_depth_2.jpg"><br>
      <code>Toilet_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Toilet_hed_1.jpg" width="160" alt="Toilet_hed_1.jpg"><br>
      <code>Toilet_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Toilet_seg_1.jpg" width="160" alt="Toilet_seg_1.jpg"><br>
      <code>Toilet_seg_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Toy_canny_1.jpg" width="160" alt="Toy_canny_1.jpg"><br>
      <code>Toy_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Toy_canny_2.jpg" width="160" alt="Toy_canny_2.jpg"><br>
      <code>Toy_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Toy_canny_3.jpg" width="160" alt="Toy_canny_3.jpg"><br>
      <code>Toy_canny_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Vegetables_hed_1.jpg" width="160" alt="Vegetables_hed_1.jpg"><br>
      <code>Vegetables_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Vegetables_hed_1_dup.jpg" width="160" alt="Vegetables_hed_1_dup.jpg"><br>
      <code>Vegetables_hed_1_dup.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Vegetables_hed_2.jpg" width="160" alt="Vegetables_hed_2.jpg"><br>
      <code>Vegetables_hed_2.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Wait_canny_1.jpg" width="160" alt="Wait_canny_1.jpg"><br>
      <code>Wait_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Wait_depth_2.jpg" width="160" alt="Wait_depth_2.jpg"><br>
      <code>Wait_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Wait_depth_3.jpg" width="160" alt="Wait_depth_3.jpg"><br>
      <code>Wait_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Wake_up_depth_2.jpg" width="160" alt="Wake_up_depth_2.jpg"><br>
      <code>Wake_up_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Wake_up_hed_1.jpg" width="160" alt="Wake_up_hed_1.jpg"><br>
      <code>Wake_up_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Wake_up_hed_3.jpg" width="160" alt="Wake_up_hed_3.jpg"><br>
      <code>Wake_up_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Wash_depth_1.jpg" width="160" alt="Wash_depth_1.jpg"><br>
      <code>Wash_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Wash_depth_2.jpg" width="160" alt="Wash_depth_2.jpg"><br>
      <code>Wash_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Wash_depth_3.jpg" width="160" alt="Wash_depth_3.jpg"><br>
      <code>Wash_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Water_canny_2.jpg" width="160" alt="Water_canny_2.jpg"><br>
      <code>Water_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Water_depth_1.jpg" width="160" alt="Water_depth_1.jpg"><br>
      <code>Water_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Water_seg_3.jpg" width="160" alt="Water_seg_3.jpg"><br>
      <code>Water_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/What_canny_2.jpg" width="160" alt="What_canny_2.jpg"><br>
      <code>What_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/What_hed_1.jpg" width="160" alt="What_hed_1.jpg"><br>
      <code>What_hed_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/What_hed_3.jpg" width="160" alt="What_hed_3.jpg"><br>
      <code>What_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/When_edge_2.jpg" width="160" alt="When_edge_2.jpg"><br>
      <code>When_edge_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/When_hed_3.jpg" width="160" alt="When_hed_3.jpg"><br>
      <code>When_hed_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/When_seg_1.jpg" width="160" alt="When_seg_1.jpg"><br>
      <code>When_seg_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Where_canny_1.jpg" width="160" alt="Where_canny_1.jpg"><br>
      <code>Where_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Where_canny_2.jpg" width="160" alt="Where_canny_2.jpg"><br>
      <code>Where_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Where_canny_3.jpg" width="160" alt="Where_canny_3.jpg"><br>
      <code>Where_canny_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Who_canny_2.jpg" width="160" alt="Who_canny_2.jpg"><br>
      <code>Who_canny_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Who_depth_3.jpg" width="160" alt="Who_depth_3.jpg"><br>
      <code>Who_depth_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Who_hed_1.jpg" width="160" alt="Who_hed_1.jpg"><br>
      <code>Who_hed_1.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Why_canny_1.jpg" width="160" alt="Why_canny_1.jpg"><br>
      <code>Why_canny_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Why_depth_2.jpg" width="160" alt="Why_depth_2.jpg"><br>
      <code>Why_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Why_depth_3.jpg" width="160" alt="Why_depth_3.jpg"><br>
      <code>Why_depth_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Worried_depth_1.jpg" width="160" alt="Worried_depth_1.jpg"><br>
      <code>Worried_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Worried_hed_2.jpg" width="160" alt="Worried_hed_2.jpg"><br>
      <code>Worried_hed_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Worried_hed_3.jpg" width="160" alt="Worried_hed_3.jpg"><br>
      <code>Worried_hed_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/Yes_depth_1.jpg" width="160" alt="Yes_depth_1.jpg"><br>
      <code>Yes_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Yes_depth_2.jpg" width="160" alt="Yes_depth_2.jpg"><br>
      <code>Yes_depth_2.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/Yes_seg_3.jpg" width="160" alt="Yes_seg_3.jpg"><br>
      <code>Yes_seg_3.jpg</code>
    </td>
  </tr>
  <tr>
    <td align="center" valign="bottom">
      <img src="data/You_canny_3.jpg" width="160" alt="You_canny_3.jpg"><br>
      <code>You_canny_3.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/You_depth_1.jpg" width="160" alt="You_depth_1.jpg"><br>
      <code>You_depth_1.jpg</code>
    </td>
    <td align="center" valign="bottom">
      <img src="data/You_depth_2.jpg" width="160" alt="You_depth_2.jpg"><br>
      <code>You_depth_2.jpg</code>
    </td>
  </tr>
</table>

