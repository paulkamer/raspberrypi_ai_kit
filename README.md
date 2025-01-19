# Raspberry PI 5 with the AI HAT+ (Hailo-8L)

## Install (Ansible)

```sh
ansible-playbook -i ansible/inventory.ini ansible/pi5_playbook.yml --ask-pass
```


## Usage

### Hailo examples

```sh
cd ~/Documents/projects/hailo/hailo-rpi5-examples

source setup_env.sh
```

```sh
# use ' --input rpi' to use input from the attached Raspberry Pi camera

# Detection example
python basic_pipelines/detection.py

# Pose estimation
python basic_pipelines/pose_estimation.py

# Instance Segmentation
python basic_pipelines/instance_segmentation.py
```



## Resources
- [AI HAT+ ](https://www.raspberrypi.com/documentation/accessories/ai-hat-plus.html)
- [AI Kit and AI HAT+ software](https://www.raspberrypi.com/documentation/computers/ai.html)
- https://github.com/hailo-ai/hailo-rpi5-examples
- [picamera2](https://github.com/raspberrypi/picamera2)

### Hailo
- https://hailo.ai
- https://community.hailo.ai/
- https://github.com/hailo-ai/hailo-rpi5-examples
- https://github.com/hailo-ai/hailo_model_zoo/tree/master/docs/public_models/HAILO8L