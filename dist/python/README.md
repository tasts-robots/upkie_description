# Upkie wheeled biped robot

<img src="https://user-images.githubusercontent.com/1189580/169594012-2d685579-2b66-4470-9def-57bd0656b420.png" align="right" width="300">

[![PyPI version](https://img.shields.io/pypi/v/upkie_description)](https://pypi.org/project/upkie_description/)

URDF description for the [Upkie](https://hackaday.io/project/185729-upkie-wheeled-biped-robot) wheeled biped. See also:

- [3D printed parts](https://www.printables.com/model/127831-upkie-wheeled-biped-robot)
- [Locomotion code](https://github.com/tasts-robots/upkie_locomotion)
- [Project log](https://hackaday.io/project/185729/logs)

Upkie's head derives from the chassis of the [mjbots quad](https://github.com/mjbots/quad).

## Python module

This module helps retrieve Upkie's model from a Python program. Import it by:

```python
import upkie_description
```

It then provides the following paths:

<dl>
    <dt>
        <code>upkie_description.path</code>
    </dt>
    <dd>
        Path to the "upkie_description" folder itself.
    </dd>
    <dt>
        <code>upkie_description.meshes_path</code>
    </dt>
    <dd>
        Path to the "meshes" folder.
    </dd>
    <dt>
        <code>upkie_description.urdf_path</code>
    </dt>
    <dd>
        Path to the URDF file of the model.
    </dd>
</dl>
