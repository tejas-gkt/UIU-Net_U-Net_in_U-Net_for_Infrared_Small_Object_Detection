# UIU-Net_U-Net_in_U-Net_for_Infrared_Small_Object_Detection
“U-Net in U-Net” framework, UIU-Net for short, and detect small objects in infrared images. Embeds a tiny U-Net into a larger U-Net backbone, enabling the multi-level and multi-scale representation learning of objects.

**MAIN PROGRAM:**
1. IMPORT libraries (torch, torchvision, numpy, matplotlib, etc.)
2. DEFINE UIU-Net model architecture:
   - REBNCONV blocks
   - RSU blocks with proper channel management
   - Interactive Cross Attention modules
   - Resolution Maintenance Deep Supervision
3. CREATE synthetic infrared dataset
4. SET UP training pipeline:
   - Data loaders
   - Loss function (BCE)
   - Optimizer (Adam)
   - Training loop
5. TRAIN model on synthetic data
6. EVALUATE model performance
7. VISUALIZE results
8. TEST with custom images




**Citation**
 @article{wu2023uiu,
  title     = {UIU-Net: U-Net in U-Net for Infrared Small Object Detection},
  author    = {X. Wu and D. Hong and J. Chanussot},
  journal   = {IEEE Trans. Image. Process.}, 
  volume    = {32},
  pages     = {364--376},
  year      = {2023},
  publisher = {IEEE}
 }


