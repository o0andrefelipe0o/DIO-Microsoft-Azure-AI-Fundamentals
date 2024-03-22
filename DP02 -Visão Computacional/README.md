<h1>
<a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/f38a62b8-2880-4fd2-82ff-ba263ce97cdb.png">
</a>
Reconhecimento Facial e transformação de imagens em Dados
</h1>

# Adicionando legendas às imagens

**Há muitas ferramentas disponíveis no [Vision Studio](https://portal.vision.cognitive.azure.com/gallery/featured), mas resolvi abordar sobre a [Add captions to imagens](https://portal.vision.cognitive.azure.com/demo/image-captioning) porque percebo uma tentativa de implementar a autodescrição em eventos, aulas, palestras e tudo mais para que os deficientes visuais consigam se situarem melhor no momento.**

[Add captions to imagens](https://portal.vision.cognitive.azure.com/demo/image-captioning) permite com que recursos de inteligência artificial ofereça uma descrição detalhada do que se encontra em imagens como fotos e vídeos para deficientes visuais.

# Como configurar

**1.** Abrir o [Vision Studio](https://portal.vision.cognitive.azure.com/gallery/featured) (https://portal.vision.cognitive.azure.com/gallery/featured) e selecionar [Image analysis](https://portal.vision.cognitive.azure.com/gallery/imageanalysis):

**2.** Selecione a opção [Add captions to imagens](https://portal.vision.cognitive.azure.com/demo/image-captioning):

**3.** Arraste e solte um arquivo na caixinha de upload ou selecione dentro da mesma caixinha a opção *"Browse for a file"* para procurar um arquivo ou *"Take a photo"* para tirar uma foto:

**4.** Mantenha a opção *"Detected attributes"* (Atributos detectados) selecionada para visualizar a descrição de imagem que a ferramenta criou:

**5.** Selecione *"JSON"* para visualizar o código .json gerado:

```
{
  "apim-request-id": "ad93e6b8-a4b9-4533-95d4-7dbcc51a5055",
  "content-length": "165",
  "content-type": "application/json; charset=utf-8",
  "modelVersion": "2023-10-01",
  "captionResult": {
    "text": "a man sitting at a desk with a laptop",
    "confidence": 0.7625073194503784
  },
  "metadata": {
    "width": 1280,
    "height": 853
  }
}
```