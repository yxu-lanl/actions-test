#convert docs to md with pandoc
pandoc --extract-media ./QuickStart_img QuickStart_v1.docx -o QuickStart.md
pandoc --extract-media ./MetaAnnotation_img 1d_Metagenome_Annotation_User_Guide_v1.2.docx -o metaAnnotationUserGuide.md
