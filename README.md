
# <font face = "verdana"> Music Generation using Deep Learning </font>

<font face = "verdana">Sequence models have been the most popular choice for modelling music. More recently, Transformer based architectures that use self-attention mechanisms are proven to be more effective in capturing long-term dependencies.<br><br>
The work done in this project is an attempt at generating original compositions that are similar in style to that of the artist. One approach is to treat the problem as a Lanugage Modelling Task and leverage state-of-the art transformer based architectures to learn music structure.<br>
<br>This project is inspired from <b> [OpenAI's MuseNet](https://openai.com/blog/musenet/)</font>

![BertGif](https://3.bp.blogspot.com/-VOpQfkfBY5A/WPxB1dKTd4I/AAAAAAAAaJg/1J_pVxoz1kcUhvNPQ-mbV1moWuIVN9ScQCLcB/s1600/bert_ernie_garage_band.gif)

## Objective <br>
<font face = "verdana"><b> Given a collection of music from a popular artist, generate new <I>"meaningful"</I> music compositions that are able to capure the <i>"<u>structure</u>"</i> and <i>"<u>style</u>"</i> of the original artist.</b></font>


## Approach <div style="text-align:right"><font size="1">Check out my <a href="./Images/Poster.png">poster</a> for the project!</font></div>
<font face="verdana">
<b>1. Pre-Processing</b>
    <div style="width: 450px;">![preprocess.png](attachment:preprocess.png)<br></div>
    <td>
<b>2. Discretization of Spectrograms using Vector Quantization</b>
    <div style="width: 450px;">![VQ.png, 20%](attachment:VQ.png)<br></div>
<b>3. Training with BERT and using Masked Language Modelling  (MLM) for Music Generation</b>
<br><br>
    <div style="width: 450px;">![bertgen.png](attachment:bertgen.png)<br></div>
</font>

## Setup
<b>Requirements</b>
    - Python 3.7
    - Jupyter Notebooks
    - Latest version of Librosa
    
<b>Instructions</b>
    - Download BERTGen.ipynb and open using jupyter notebook.
    - Install Pytorch Prtrained BERT Model
    - Download provided VQ files (.csv) and associated codebook
    - Now provide your input audio sequences and watch BERT generate a new composition!
