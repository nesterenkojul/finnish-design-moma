# Finnish Design In MoMA’s Collection – A Look Through Data, Visualisation And Material Composition
Supporting data and code for the research project on the representation of Finnish design in the collection of the Museum of Modern Art, New York. Project paper is included in this repository under [_Finnish_Design_MoMA.pdf_](https://github.com/nesterenkojul/finnish-design-moma/tree/main/Finnish_Design_MoMA.pdf)

<br>

### Sources of raw data
1. [The Museum of Modern Art (MoMA) Collection Dataset](https://github.com/MuseumofModernArt/collection)
2. [Finna.fi Database](http://finna.fi) (collected via an [API](https://www.kiwi.fi/spaces/Finna/pages/53839221/Finna+API+in+English))

Scraped, filtered, and minimally processed data is stored in the [_data_raw_filtered_](https://github.com/nesterenkojul/finnish-design-moma/tree/main/data_raw_filtered) folder. Images are also available in the [_moma_imgs_](https://github.com/nesterenkojul/finnish-design-moma/tree/main/finna_imgs) and [_finna_imgs_](https://github.com/nesterenkojul/finnish-design-moma/tree/main/finna_imgs) folders.

### Data processing
The whole process of data collection, transformation and visualisation is described in the [_MoMA_vs_Finna.ipynb_](https://github.com/nesterenkojul/finnish-design-moma/blob/main/MoMA_vs_Finna.ipynb) notebook.

The final version of the resulting dataset is stored in the [_data_final_](https://github.com/nesterenkojul/finnish-design-moma/tree/main/data_raw_final) folder.

### Classification of artwork materials
In the [_Clip_Finna.ipynb_](https://github.com/nesterenkojul/finnish-design-moma/blob/main/Clip_Finna.ipynb) notebook, the CLIP model is applied to a set of images from Finna to determine the main compositional material of an object (this version was run in Google Colab).

Datasets updated with medium classification are stored in the [_data_preprocessed_](https://github.com/nesterenkojul/finnish-design-moma/tree/main/data_preprocessed) folder.

### Visualisations

For visualising the structure of the collections along with their visual representations, [PIDA – Playful Interface for Digital Archives](https://nesterenkojul.github.io/pida/) was used. Visualisations produced with it are stored in the [_pida_visualisations_](https://github.com/nesterenkojul/finnish-design-moma/tree/main/pida_visualisations) folder. Due to the limitations of the tool, it requires the data to be in a specific format. Versions of the dataset which can be used with the tool are stored in the [_data_for_pida_](https://github.com/nesterenkojul/finnish-design-moma/tree/main/data_for_pida) folder.

Statistical visualisations produced with Python are stored in the [_charts_](https://github.com/nesterenkojul/finnish-design-moma/tree/main/charts) folder.
