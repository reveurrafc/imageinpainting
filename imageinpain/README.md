Setup
Clone this repo
git clone https://github.com/reveurrafc/imageinpainting.git

Install the required libraries(./requirements.txt)

### Run
- Quick Run
```
python predict.py
```

- You can specify an image / a mask / a model paths
```
python predict.py --img <image_path> --mask <mask_path> --model <model_path>
```

## Train and Test
- Copy the config yaml file.
```
cd partialconv/
cp default-config.yml config.yml
```
- Customize `config.yml`
- Run `main.py`
