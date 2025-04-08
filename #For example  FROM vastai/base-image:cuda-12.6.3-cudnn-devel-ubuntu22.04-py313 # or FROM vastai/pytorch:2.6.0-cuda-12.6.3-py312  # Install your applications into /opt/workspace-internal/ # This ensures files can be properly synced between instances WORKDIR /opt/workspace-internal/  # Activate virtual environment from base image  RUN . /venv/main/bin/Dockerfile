FROM vastai/pytorch:2.6.0-cuda-12.6.3-py312

# Install your applications into /opt/workspace-internal/
# This ensures files can be properly synced between instances
WORKDIR /opt/workspace-internal/

# Activate virtual environment from base image 
RUN . /venv/main/bin/activate

RUN git clone https://github.com/Wan-Video/Wan2.1
