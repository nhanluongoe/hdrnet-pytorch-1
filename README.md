# Deep Bilateral Learning for Real-Time Image Enhancements

Unofficial PyTorch implementation of 'Deep Bilateral Learning for Real-Time Image Enhancement', SIGGRAPH 2017 https://groups.csail.mit.edu/graphics/hdrnet/

Python 3.6

### Dependencies

To install the Python dependencies, run:

    pip install -r requirements.txt
    
## Datasets

Exported from Adobe FiveK

*Input*: https://drive.google.com/file/d/1igfH2fkZE_cA-TJtQMr8BOn08HGNJTcE/view?usp=sharing

*Output*: https://drive.google.com/file/d/1iItOVPOpzUU_3R6mq2d8sZxczJSmVNZM/view?usp=sharing
## Usage

    
To train a model, run the following command:

    python train.py --test-image="test_image.jpg" --dataset="/dataset_path" --lr=0.0001
    
    
To test image run:

    python test.py --checkpoint="checkpoint_path.pth" --input="./test_image.jpg" --output="out.png"
    
